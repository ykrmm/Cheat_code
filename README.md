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
