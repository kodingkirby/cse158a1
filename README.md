# cse 158 data mining hw3

## getting started:
First, log into the EC2 instance and forward port 8888 (for jupyter)

'''
ssh -i headlinerKey.pem ubuntu@ec2-54-187-73-110.us-west-2.compute.amazonaws.com -L 8000:localhost:8888
'''

Then, clone your git repo to the home directory
'''
git clone https://github.com/kodingkirby/cse158hw3.git
'''

Might have to change permissions on nvme
sudo chown username:ubuntu /data

Select a python env and start the notebook
'''
conda activate py37
cd /data/cse158hw3
jupyter notebook
'''

Now go to your browser and navigate to localhost:8000
It will ask you for a token probably, which you'll find in the terminal window when you start jupyter

