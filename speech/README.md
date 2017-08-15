* Google cloud SDKインストール  

https://cloud.google.com/sdk/docs/quickstart-debian-ubuntu  

* サービスアカウントを作成

https://cloud.google.com/speech/docs/common/auth#set_up_a_service_account

* quick-start

https://cloud.google.com/speech/docs/getting-started

* ストリーム認識のサンプルを動かしてみる

音声関係のライブラリをインストール  
sudo apt-get install portaudio19-dev  
sudo apt-get install python-pyaudio  

googleのサンプルを入手  
git clone https://github.com/GoogleCloudPlatform/python-docs-samples.git  

認証情報の環境変数を設定する。  
export GOOGLE_APPLICATION_CREDENTIALS=/path/to/service_account.json  

ストリーミング認識のサンプルを動かす。  
speech/cloud-client/transcribe_streaming_mic.py

