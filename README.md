# aws-python-lambdas
Collection of python lambda function

## Setup Conda Env
<pre># create env
conda env create -n aws-python-lambdas -f conda-dev-env.yml
# activate env
source activate aws-python-lambdas
# after installing new libs update conda-dev-env.yml
conda env export --file conda-dev-env.yml 
</pre>

## Building

<pre># build lambda function contained inside src/hello_world
python build.py --src-path src/hello_world --dist-path dist
</pre>
