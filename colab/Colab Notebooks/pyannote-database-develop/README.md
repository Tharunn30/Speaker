!pip install git+https://github.com/pyannote/pyannote-audio.git@develop


%cd /content/MyDrive/pyannote-database-develop
!python setup.py install


%cd SRM-diarization-setup-main/
!python train-test.py

