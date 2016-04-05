# Noembed docker instance

This is the Noembed Docker image.

To run it do:

docker run -p 5000:5000 -t nicopace/noembed

If you have a twitter auth json, you can copy it into the share folder and mount the volume like this

docker run -p 5000:5000 -v files/share:/usr/src/myapp/share -t nicopace/noembed

As a guide, a sample twitter_cred.json is provided... please complete with your own data.
