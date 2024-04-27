# Transcription 
* This command is for making transcription they are path sensitive
* For Hindi hypothesis file
```bash
deepspeed  transcribe.py '/mnt/e/iit-bombay-internship/vistaar/jsons/mini.json' \
    '/mnt/e/iit-bombay-internship/hindi_models/hindi_models/whisper-medium-hi_alldata_multigpu/' \
    'hindi' \
    10 \
    '/mnt/e/iit-bombay-internship/vistaar/output/output_3.txt'
```

* For Mallyalam hypothesis file
```bash
deepspeed  transcribe.py '/mnt/e/iit-bombay-internship/vistaar/output/mallu_manifest.json' \
    '/mnt/e/iit-bombay-internship/vistaar/model/malayalam_models/malayalam_models/whisper-medium-ml_alldata_multigpu/'   \
    'malayalam' \
    10 \
    '/mnt/e/iit-bombay-internship/vistaar/output/mallu_hyp.txt'
```
