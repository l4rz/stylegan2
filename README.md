## StyleGAN2

# stuff added/changed:
* networks_stylegan2.py: includes attention implementation by @theshawwn https://github.com/shawwn/stylegan2 in both G and D (todo: make it config param via kwargs)
* training_loop.py: added feed_dict_d, changed ops execution to allow setting G_lrate and D_lrate separately; metrics.run commented out; added gpu_options=tf.GPUOptions(allow_growth=True)
