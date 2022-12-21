```
pip install -r requirements.txt
```
Install fused_dense_lib
```
cd training_results_v2.0/HazyResearch/benchmarks/bert/implementations/pytorch/csrc/fused_dense_lib
python setup.py install
```
```
composer ./train.py -f /home/sixifang/training_results_v2.1/MosaicML/benchmarks/bert/implementations/8xA100_80GB-baseline/config.yaml
```