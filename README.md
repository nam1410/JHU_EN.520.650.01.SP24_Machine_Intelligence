# First Project, Solving 8_Queens Problem

n-Queens puzzle is a classic problem in combinatorial optimization involving the strategic placement of n queens on a chessboard without any mutual attacks. 
We investigate different algorithms covering Breadth-First Search (BFS), Depth-First Search (DFS), Hill Climbing, Simulated Annealing, Backtracking, and Brute Force, each compared with run time, memory, and overall approach in solving the puzzle. While BFS performs expansive exploration of the solution space, it necessitates substantial memory to accommodate its breadth-wise traversal. 
In contrast, DFS pursues a deeper path, delving into the solution space with precision. Local search algorithms like Hill Climbing and Simulated annealing iteratively refine solutions towards an optimal configuration. Backtracking ensures a thorough exploration of potential solutions albeit at the cost of heightened computational demands. Lastly, the simple Brute Force approach exhaustively evaluates every possible configuration. We evaluate the strengths and limitations of each algorithm in the context of an 8-Queens puzzle.

# Second Project, Comparative Analysis of Adversarial Attacks and Defense Methods
In this project, we explore and contrast the impacts of multiple adversarial
 attacks, including Projected Gradient Descent (PGD), noise-based attacks, Fast
 Gradient Sign Method (FGSM), Carlini & Wagner (C&W), DeepFool, Feature
 importance-aware Attack(FIA), and Jacobian-based Saliency Maps(JSM) on three
 distinct neural network architectures, using the CIFAR-10 dataset. The models
 evaluated include a custom-trained simple Convolutional Neural Network (CNN),
 a pre-trained ResNet-18, and a Tiny Vision Transformer (Tiny-VIT) which has
 been specifically trained on the CIFAR-10 dataset. We employ a range of de
fense strategies, such as adversarial training, denoising through trained DnCNN,
 and regularization techniques, to mitigate the effects of these attacks. The perfor
mance of each model is meticulously assessed by comparing their accuracy under
 various adversarial conditions. This comparative analysis aims to elucidate the rel
ative effectiveness and shortcomings of each attack and defense method, providing
 insight into their practical implications in securing neural networks against adver
sarial threats. 
