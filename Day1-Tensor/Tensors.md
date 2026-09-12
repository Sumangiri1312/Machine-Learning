# Tensor
A tensor is a mathematical object that generalizes scalars, vectors, and matrices to higher dimensions.

### Types
#### 1. 0D Tensor (Scalar)
A single number: 5

Example:
- Temperature = 30°C
- Age = 20

#### 2. 1D Tensor (Vector)
A list of numbers:
[10, 20, 30, 40]
Shape:  (4,)

#### 3. 2D Tensor (Matrix)
Rows and columns:
[
 [1, 2, 3], 
 [4, 5, 6]
]
Shape:
(2, 3)

Example:
- Student marks table
| Math | Science | English |
| ---- | ------- | ------- |
| 80   | 75      | 90      |
| 85   | 92      | 88      |


#### 4. 3D Tensor
A collection of matrices:
[
 [[1,2],[3,4]],
 [[5,6],[7,8]]
]
Shape: 
(2, 2, 2)

Meaning:
- 2 matrices
- Each matrix has 2 rows
- Each row has 2 columns
- 
##### Example: Color Image
A color image is a 3D tensor.
Suppose an image has:

- Height = 224
- Width = 224
- Channels = 3 (Red, Green, Blue)
Shape:
(224, 224, 3)

#### 5. 4D Tensor
When training neural networks, we usually process many images together.

Suppose:
- 32 images
- Each image: 224 × 224 × 3

Shape:
(32, 224, 224, 3)

Here:
32 = batch size
224 = height
224 = width
3 = RGB channels
This is a 4D tensor.

#### 6. 5D Tensor
A 5D tensor has 5 axes (dimensions).
A common example in Deep Learning is a batch of videos.

Suppose you have:
16 videos
Each video has 30 frames
Each frame is 224 × 224 pixels
RGB image (3 channels)

Shape:
(16, 30, 224, 224, 3)
Meaning:
| Dimension | Meaning                       |
| --------- | ----------------------------- |
| 16        | Number of videos (batch size) |
| 30        | Frames per video              |
| 224       | Height                        |
| 224       | Width                         |
| 3         | RGB channels                  |


### Rank, Axes, shape
no. of axis = Rank = No of dimensions
