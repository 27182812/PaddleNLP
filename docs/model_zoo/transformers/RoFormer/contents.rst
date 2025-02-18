

------------------------------------
RoFormer模型汇总
------------------------------------



下表汇总介绍了目前PaddleNLP支持的RoFormer模型对应预训练权重。
关于模型的具体细节可以参考对应链接。

+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
| Pretrained Weight                                                                | Language     | Details of the model                    |
+==================================================================================+==============+=========================================+
|``roformer-chinese-small``                                                        | Chinese      | 6-layer, 384-hidden,                    |
|                                                                                  |              | 6-heads, 30M parameters.                |
|                                                                                  |              | Roformer Small Chinese model.           |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-base``                	                                       | Chinese      | 12-layer, 768-hidden,                   |
|                                                                                  |              | 12-heads, 124M parameters.              |
|                                                                                  |              | Roformer Base Chinese model.            |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-char-small``                                                   | Chinese      | 6-layer, 384-hidden,                    |
|                                                                                  |              | 6-heads, 15M parameters.                |
|                                                                                  |              | Roformer Chinese Char Small model.      |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-char-base``                                                    | Chinese      | 12-layer, 768-hidden,                   |
|                                                                                  |              | 12-heads, 95M parameters.               |
|                                                                                  |              | Roformer Chinese Char Base model.       |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-sim-char-ft-small``                                            | Chinese      | 6-layer, 384-hidden,                    |
|                                                                                  |              | 6-heads, 15M parameters.                |
|                                                                                  |              | Roformer Chinese Char Ft Small model.   |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-sim-char-ft-base``                                             | Chinese      | 12-layer, 768-hidden,                   |
|                                                                                  |              | 12-heads, 95M parameters.               |
|                                                                                  |              | Roformer Chinese Char Ft Base model.    |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-sim-char-small``                                               | Chinese      | 6-layer, 384-hidden,                    |
|                                                                                  |              | 6-heads, 15M parameters.                |
|                                                                                  |              | Roformer Chinese Sim Char Small model.  |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-chinese-sim-char-base``                                                | Chinese      | 12-layer, 768-hidden,                   |
|                                                                                  |              | 12-heads, 95M parameters.               |
|                                                                                  |              | Roformer Chinese Sim Char Base model.   |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-english-small-discriminator``                                          | English      | 12-layer, 256-hidden,                   |
|                                                                                  |              | 4-heads, 13M parameters.                |
|                                                                                  |              | Roformer English Small Discriminator.   |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+
|``roformer-english-small-generator``                                              | English      | 12-layer, 64-hidden,                    |
|                                                                                  |              | 1-heads, 5M parameters.                 |
|                                                                                  |              | Roformer English Small Generator.       |
+----------------------------------------------------------------------------------+--------------+-----------------------------------------+