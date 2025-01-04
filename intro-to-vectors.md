
# Table of Contents

1.  [Intro to vectors](#orgaef0e4f)
    1.  [Linear combinations](#org4dfd96f)
    2.  [2-Dimensional Vectors](#org4f4432b)



<a id="orgaef0e4f"></a>

# Intro to vectors

\begin{equation}
cv + dw = c \begin{bmatrix} 1 \\ 1 \end{bmatrix} + d  \begin{bmatrix} 2 \\ 3 \end{bmatrix} = \begin{bmatrix} c + 2d \\ c + 3d \end{bmatrix}
\label{eq1}
\tag{1.0}
\end{equation}


<a id="org4dfd96f"></a>

## Linear combinations

-   A linear combination of $c = 1$ & $d = 1$ for the equation 1 will produce the following output:

\begin{equation}
v + w =
\begin{bmatrix} 1 \\ 1 \end{bmatrix} +
\begin{bmatrix} 2 \\ 3 \end{bmatrix} =
\begin{bmatrix} 3 \\ 4 \end{bmatrix}
\label{eq2}
\tag{1.1}
\end{equation}

-   $\therefore$ a linear combination is the addition of vectors and multiplying their scalars


<a id="org4f4432b"></a>

## 2-Dimensional Vectors

\begin{equation}
\ltag{\textbf{Column Vector}}
\hspace{1cm}
v = \begin{bmatrix}v_1 \\ v_2 \end{bmatrix}
\label{Column Vector}
\tag{1.2.0}
\end{equation}

-   A column vector has 2 seperate numbers $v_1$ and $v_2$ which produces a 2-dimensional vector $v$
-   Although $v_1$ and $v_2$ cannot be added, we can add other vectors together

\begin{equation}
\ltag{\textbf{Vector Addition}}
\hspace{1cm}
v = \begin{bmatrix}v_1 \\ v_2 \end{bmatrix} \text{and }
w = \begin{bmatrix}w_1 \\ w_2 \end{bmatrix} \text{add to }
v + w = \begin{bmatrix}v_1 + w_1 \\ v_2 + w_2 \end{bmatrix}
\label{Vector Addition}
\tag{1.2.1}
\end{equation}

-   Subtraction follows the same idea, such that $v - w$ is $v_1 - w_1$ and $v_2 - w_2$
-   Scalar multiplication can be represented as:

\begin{equation}
\ltag{\textbf{Scalar Multiplication}}
\hspace{2cm}
2v = \begin{bmatrix}2v_1 \\ 2v_2 \end{bmatrix}  = v + v \text{ and}
-v = \begin{bmatrix}-v_1 \\ -v_2 \end{bmatrix}
\label{Scalar Multiplication}
\tag{1.2.2}
\end{equation}

-   In the above equation, 2 is the scalar, $c$ , of the vector  $v$
-   The sum of $-v$ and $v$ is the zero vector, $0$ and has components 0 and 0

Thus, the sum of  $cv$ and $wd$  is the <span class="underline">linear combination</span>,   $cv + dw$.
