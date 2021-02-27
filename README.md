# streamlit-docker-aws

git clone https://github.com/Frenz86/streamlit-docker-aws.git
cd streamlit-docker-aws
sudo docker image build -t streamlit:app .
sudo docker run --name streamlitwebapp -it -p 8501:8501 -d streamlit:app
