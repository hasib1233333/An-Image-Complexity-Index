Title:

An Image Complexity Index for Adaptive Contrast-Limited Histogram Equalization
Abstract:

Contrast Limited Adaptive Histogram Equalization (CLAHE) depends on a clip limit and a tile size that are usually fixed for an entire image set, even though the right enhancement strength differs with image content. We define the Image Complexity Index (ICI), a weighted sum of normalized Shannon entropy, Sobel gradient energy, and gray-level co-occurrence texture heterogeneity, and use it to set the clip limit, tile size, and a brightness-preservation blend weight from a single image, with no search and no training. On a 96-image benchmark (24 base images under clean, low-light, noisy, and foggy conditions) the method significantly improves brightness preservation and fidelity over four classical histogram-based methods, is not significantly different from an entropy-curvature adaptive baseline, and is outperformed by a particle swarm search baseline and by a pretrained zero-reference low-light network on some metrics, at a small fraction of their computational cost. A leave-one-component-out study shows that entropy alone, not the full three-term index, drives the improvement, and we report this directly rather than presenting the three-component formulation as necessary.
Keywords:

histogram equalization, CLAHE, image complexity, adaptive enhancement, contrast enhancement, particle swarm optimization
