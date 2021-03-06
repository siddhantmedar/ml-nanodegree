## Feature Transformation
- Feature Transformation: Pre-processing a set of features to create a new (smaller / more compact) feature set, 
while retaining as much as (relevant / useful) information as possible.
- Why
  - lots of words
  - good indicator
  - polysemy: car (automobile, LISP cons cell)
  - synonomy
- Independent Component Analysis
  - PCA ~ correlation, maximizing variance => reconstruction
  - ICA ~ independence
    - [x_1, x_2, ..., x_i] -> [y_1, y_2, ..., y_i]
    - I: mutual information
    - I(y_i, y_j) = 0
    - I(y;x) => as high as possible
- Blind Source Seperation (Cocktail Party)
- PCA vs ICA

  | PCA        | ICA           |
  |:-------------:|:-------------:|
  | mutually orthogonal       | mutually independent |
  | maximal variance      | maximal mutual information |
  | ordered features | bag of features |
  
  || PCA        | ICA           |
  |:-------------:|:-------------:|:-------------:|
  | blind source seperation | No | Yes |
  | directional      | No | Yes |
  | faces | brightness, average face | nose, mouth.. |
  | natural scences |  | edges |
  | documents |  | topics |

- Alternatives
  - RCA = Random Component Analysis
    - Generates random directions => works for classification
    - Advantages: fast
  - LDA = Linear Discriminant Analysis
    - Finds a projection that descriminants based on the label
- Summary
  - A is for analysis! PCA, ICA, LDA, RCA
  - relations between different transformation
  - analysis of the data -> structure
  - probability vs linear algebra
