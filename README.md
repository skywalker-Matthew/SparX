# SushiBelt Architecture - Toy Model

This is a toy model of the SushiBelt architecture with the following configuration:
- Array size \(N = 16 \times 16\)
- Sparsity of weights and activations: 0.5
- FIFO depth of each PE: \(K = 16\)

## Image Explanation:
1. The black dots flowing in from the left and top represent non-zero data, while zero data is not shown.
2. Each square represents a PE and its FIFO. The number inside the square represents the number of items in the FIFO, and the progress bar below the square shows the progress of the PE executing a single multiplication.
3. The average PE utilization is displayed at the bottom of the screen.
