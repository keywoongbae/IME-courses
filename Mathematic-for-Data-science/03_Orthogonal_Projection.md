## 03. Orthogonal Projection

### Orthogonal projection

- 정의
  - $\R ^n$에 포함되는 부분집합 $\mathcal{L}$에 대해서, $\mathcal{L}$의 직교 여공간(Orthogonal Complement)는 다음과 같이 정의됨.
    - $\mathcal{L}^{\bot}= \{\text{x} \in \R^{n} : \text{x}^T \text{y} = 0 \ \ \forall \text{y} \in \mathcal{L}  \}$
- 이론
  - $\mathcal{L}^{\bot}$은 $\R^n$의 부분집합이며, $\mathcal{L}$과  $\mathcal{L}^{\bot}$은 교집합이 없음.  $(\mathcal{L} \cap \mathcal{L}^{\bot} = \{0\})$
- 이론
  - $\R^n$에 속하는 $\text{x}$는 아래와 같이 표현될 수 있음.
    - $\text{x} = \text{x}_{\mathcal{L}} + \text{x}_{\mathcal{L^{\bot}}}$
    - 이때, $\text{x}_{\mathcal{L}} \in \mathcal{L} \and \text{x}_{\mathcal{L^{\bot}}} \in \mathcal{L^{\bot}}$
    - $\text{x}_{\mathcal{L}}$를 $\mathcal{L}$에 대한 $\text{x}$의 직교사영이라고 함.
- 이론
  - $\mathcal{L}$에 속하는 모든 $\text{y}$에 대하여 $||\text{x}-\text{x}_{\mathcal{L}}||_2 \leq ||\text{x} - \text{y}||_2$
    - <img src=".\img\image-20230919233904196.png" alt="image-20230919233904196" style="zoom:150%;" />
- 정의
  - 만약 $A^2 = A$라면, $\R^{n \times n}$에 속하는  행렬 A를 멱함수(idempotent, projection) 행렬이라고 함.
- 이론
  - (1) $\text{Ax}$는 $\R^n$에 속하는 모든 $\text{x}$의 $\mathcal{C}(A)$에 대한 직교 투영임.
  - (2) $A$는 사영이고, $\mathcal{N}(A) \bot \mathcal{C}(A)$이며, $\text{x}\in \mathcal{N}(A) \and \text{y} \in \mathcal{C}(A)$인 $\text{x}, \text{y}$에 대해서 $\text{x}^T \text{y}=0$임.
  - (3) $A$는 대칭이고 멱함수임.
- 정의
  - 만약 위 중 하나가 성립하면, A를 $\mathcal{C}(A)$에 대한 직교사영 행렬이라고 함.
