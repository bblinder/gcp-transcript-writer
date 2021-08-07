# gcp-transcript-writer
Using Google's Speech-to-Text neural engine to transcribe podcasts and videos

1. Create your workspace
2. Enable the **Speech-to-Text API**
3. Create nd set your service account permissions
4. Set the environment variable `GOOGLE_APPLICATION_CREDENTIALS` to the path of the JSON file that contains your service account key. This variable only applies to your current shell session, so if you open a new session, set the variable again


## Resources
https://cloud.google.com/speech-to-text/docs/quickstart-client-libraries?hl=en_US
https://cloud.google.com/speech-to-text/docs/async-recognize?hl=en_US
