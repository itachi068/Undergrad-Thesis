This study presents an effective approach that aims to improve and classify video encoding
processes by utilizing the capabilities of machine learning algorithms. The encoding process
begins by utilizing the VTM 22.0 codec to accurately record important metrics such as encoding
length, Peak Signal-to-Noise Ratio (PSNR), and bit rate. By examining each frame in detail, we
carefully extract statistical parameters such as mean, median, mode, and variance from discrete
32x32 blocks. This allows us to gain a detailed picture of the properties of the image. Integrating partition mode level data enhances the encoding process. In order to facilitate thorough
analysis and training of models, a strong dataset is carefully chosen, including insights from
several video sequences. This dataset is essential for the subsequent training phase, during
which a decision tree model is implemented. By undergoing intensive training on this combined dataset, the decision tree acquires the ability to identify patterns and connections among
features such as mean, median, mode, variance, and the decision variable class_level.The results indicate a significant decrease in the time it takes to encode in the changed version, but
the bitrate shows a minor increase. The suggested methodology effectively optimizes and categorizes video encoding jobs by striking a careful balance between time efficiency and bitrate
preservation. Specifically, the analysis demonstrates a stunning 42.15% reduction in encoding
time, followed by a minor sacrifice of 2.61% bitrate units which were generated from thorough
evaluations across 11 unique video sequences.
