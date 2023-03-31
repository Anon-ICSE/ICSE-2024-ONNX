# NNSmith Adapted
The `nnsmith` folder is cloned at the following commit-id: [`8cee6f6a760a4e8b91a910462986c968aaddb01c`](https://github.com/ise-uiuc/nnsmith/tree/8cee6f6a760a4e8b91a910462986c968aaddb01c), on March 8, 2023.


We generate synthetic models using the following way:
```
python cust_gen.py mgen.max_nodes=(n-nodes) mgen.num_gen=100 model.type=(torch-onnx|tensorflow-onnx)
```

We generate constrained models in the following way:
```
python cust_gen.py mgen.max_nodes=(n-nodes) mgen.num_gen=100 model.type=(torch-onnx|tensorflow-onnx) mgen.exclude="[core.Tan, core.Where, core.Cos, core.Max, core.ArgMax, core.LeakyRelu, core.ArgMin, core.Erf, core.Trilu, core.AveragePool, core.Atan]" mgen.dtypes_choices='[f32]'
```