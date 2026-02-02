conda create -n neuspell_eval_env python=3.9

python -m pip install https://github.com/allenai/allennlp.git

python -m pip install -e .

python -m pip install --upgrade pip setuptools wheel
python -m pip install blis

python -m pip install git+https://github.com/allenai/allennlp.git


