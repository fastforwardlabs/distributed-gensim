# Distributed LDA with gensim

Work in progress attempt. Little time spent, little progress made.

The gensim [Distributed Computing](https://radimrehurek.com/gensim/distributed.html) docs.

The notebook does work, if all of nameserver, dispatcher and a worker are run on the host machine (through the terminal), i.e. non-distributed. I believe the gensim worker processes are dying immediately on the workers . One can keep the workers alive with an infinite loop after the python process (`while true; do sleep 10; done`), but without it, they launch and proceed immediately to "Success" in the session view.