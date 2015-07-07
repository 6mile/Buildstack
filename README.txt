For new Buildstack nodes launch a new ec2 instance.
AMI = ami-3f0fc054

This AMI has the Buildstack platform baked into it.  This includes:
docker 1.6.2
ansible 1.9.1
haproxy 1.5.2
pip 7.1.0 
python 2.6.6
redis 2.4.10
noip 2.1.9
git 1.7.1

After you launch a new Buildstack instance you need to run "/usr/sbin/noip2 -C" and follow the prompts.  Additionally, you will have to enable Password Authentication to yes and restart the sshd daemon.



