# gcloud-audio-to-text-tutorial

Following this tutorial: <https://cloud.google.com/speech-to-text/docs/quickstart-client-libraries>

## Steps

1. Set up env variable

    ```bash
    export GOOGLE_APPLICATION_CREDENTIALS="/Users/aa186066/code/audio-to-text-tutorial/Audio-To-Text-4e6ba91ee6ca.json"
    ```

2. Install GCloud SDK following the links they provided

3. Install client library

    ```bash
    pip install --upgrade google-cloud-speech
    ```

4. Copy code from tutorial

5. Download sample audio file from google github repo
    <https://github.com/GoogleCloudPlatform/python-docs-samples/tree/master/speech/cloud-client/resources>

6. Downloaded Audacity App to listen to .raw files
    To listen to the file, need to Import > Raw Data. Then change the rate to 16000 Hz

Working with larger file

1. Install ffmpeg
    ```bash
    brew install ffmpeg
    ```

Limitations
* up to 60mins is in free tier
* 10mb limit


TODO:
Try this one https://www.alexkras.com/transcribing-audio-file-to-text-with-google-cloud-speech-api-and-python/
