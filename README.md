# Inter-means-algorithm
Inter mean algorithm implementation for the computer vision module and Segmentation image

## Steps of the Inter_mean algorothm

1. Select an initial estimate of the threshold, 𝑇. A good initial value is the average 
intensity of the image
2. Partition the image into two groups, 𝑅1 and 𝑅2, using this threshold 𝑇.
3. Calculate the mean grey values 𝜇1 and 𝜇2 for the respective partitions of 𝑅1 and 𝑅2.
4. Select a new threshold as
  `𝑇 =(𝜇1 + 𝜇2)/2`
5. Repeat steps 2 -> 4 until 𝜇1 and 𝜇2 does not significantly change in successive iterations
