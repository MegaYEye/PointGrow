# PointGrow: Autoregressively Learned Point Cloud Generation with Self-Attention
This work presents a novel autoregressive model, PointGrow, which generates realistic point cloud samples from scratch or conditioned on given semantic contexts. This model operates recurrently, with each point sampled according to a conditional distribution given its previously-generated points. It is further augmented with dedicated self-attention modules to capture long-range interpoint dependencies during the generation process.

## Data
We provided processed point clouds from 7 categories in [ShapeNet](https://www.shapenet.org), including airplane, car, table, chair, bench, cabinet and lamp. The coordinates of those point clouds, arranged as (z, y, x), range from 0 to 1. They are sorted in the order of z, y and x, and can be downloaded from [here](https://www.dropbox.com/s/yuq4sbfqq5btune/ShapeNet7.zip).
