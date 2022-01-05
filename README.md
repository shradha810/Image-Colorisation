# Image-Colorisation
we proposed a multipath GAN based image colrization architecture guided by
saliency and edge maps. It is able to generate perceaptually plausible images especially for
landscape images containing sky, waterbodies, grounds, dogs, human-skin, and few more
categories. We also suffered few failure cases as mentioned above considering our limited
computational constraints. We were also able to generate saliency maps as a byproduct from
the given edge and grayscale input images automatically .Credit also goes to the pre-trained
resnet-architecture which helped the model to learn colorful features for the given input gray
image, thus helping us to achieve our target with very limited dataset. The addition of edge
based input along with grayscale image has been inferred from User-Guided Deep Anime
Line Art Colorization with Conditional Adversarial Networks paper, which helped us to considerably improve our result than our baseline SCGAN model across various categories
of objects.
