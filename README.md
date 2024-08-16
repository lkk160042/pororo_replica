# pororo_replica
- This project is based on **PORORO: Platform Of neuRal mOdels for natuRal language prOcessing**, developed by
**kakaobrain**.
- It includes modifications to `setup.py` file for better installation and dependency management:
  - It allows to install pororo at torch > 1.6.0, so you don't have to downgrade to Python 3.8 or CUDA
- Also, it has replaced `add_prefix_space=True` to `prepend_scheme='always'`at `tokenizers.pre_tokenizers.Metaspace` 
since `tokenizers` no longer uses `add_prefix_space`in latest version.
- You can check the installation guide or original source code at https://github.com/kakaobrain/pororo
