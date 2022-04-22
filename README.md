# Cheat_code
Raccourci pour mes commandes preférées

## Python profiler 
Simple profiler
<pre>python3 -m cProfile myscript.py </pre>
Trier par temps total
<pre>python3 -m cProfile -s tottime myscript.py</pre>


## Nohup 
La sortie ne s'affiche pas avec nohup ? 
<pre>export PYTHONUNBUFFERED=1</pre>

## Conda 
création env 
<pre>
wget https://repo.anaconda.com/archive/Anaconda3-2021.11-Linux-x86_64.sh

bash Anaconda3-2021.11-Linux-x86_64.sh

source .bashrc

conda create -n env python=3.7

conda activate env

</pre>
