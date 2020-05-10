Create a virtual env
virtualenv venv

source venv/bin/activate

Clone
git clone https://github.com/tyiannak/pyAudioAnalysis.git

Install Dependencies
pip3 install -r ./App/requirements.txt

pip3 install -r ./pyAudioAnalysis/requirements.txt

brew install ffmpeg

Install
pip3 install -e pyAudioAnalysis

Using Test.py
python3 App/app.py