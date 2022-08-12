$$
\def{\ka}{\color{#000000}\colorbox{#dddddd}{\textbf{语言基础}}}
\def{\kb}{\color{#000000}\colorbox{#f012be}{\textbf{树形结构}}}
\def{\kc}{\color{#ffffff}\colorbox{#2e7740}{\textbf{线性结构}}}
\def{\kd}{\color{#ffffff}\colorbox{#0074d9}{\textbf{~~~数~~论~~~}}}
\def{\ke}{\color{#000000}\colorbox{#7fdbff}{\textbf{~字~符~串~}}}
\def{\kf}{\color{#000000}\colorbox{#39cccc}{\textbf{动态规划}}}
\def{\kg}{\color{#ffffff}\colorbox{#3d9970}{\textbf{~~~图~~论~~~}}}
\def{\kh}{\color{#000000}\colorbox{#01ff70}{\textbf{~~~搜~~索~~~}}}
\def{\ki}{\color{#000000}\colorbox{#ffdc00}{\textbf{组合数学}}}
\def{\kj}{\color{#ffffff}\colorbox{#ff851b}{\textbf{线性代数}}}
\def{\kk}{\color{#000000}\colorbox{#ff4136}{\textbf{计算几何}}}
\def{\kl}{\color{#ffffff}\colorbox{#85144b}{\textbf{数学杂项}}}
\def{\km}{\color{#ffffff}\colorbox{#111111}{\textbf{其它内容}}}
\def{\kn}{\color{#ffffff}\colorbox{#b10dc9}{\textbf{基础算法}}}
\def{\ko}{\color{#ffffff}\colorbox{#bc8f8f}{\textbf{其它算法}}}
\def{\kp}{\color{#ffffff}\colorbox{#5f4f4f}{\textbf{排序算法}}}
\def{\kz}{\color{#ffffff}\colorbox{#e5e5e5}{\textbf{~~works~~}}}
\def{\rescol}{\color{#000000}}
\def{\A}{\color{#ffffff}\colorbox{#11ee11}{\texttt{prosperitas}}} %搞定！It;s a piece of cake!/oh/hsh
\def{\B}{\color{#ffffff}\colorbox{#ee1111}{\texttt{~deficient~}}} %太难了，没学会/kk
\def{\C}{\color{#aaaaaa}\colorbox{#eeeeee}{\texttt{~~nihilum~~}}} %这个知识点是啥/yiw
\def{\D}{\color{#777777}\colorbox{#eeff11}{\texttt{inperfectum}}} %我……好像懂了……又好像没懂/yun
\def{\E}{\color{#ffffff}\colorbox{#aaee11}{\texttt{~in~charta~}}} %我只能纸上谈兵啊/fad
\def{\U}{\color{#444444}\colorbox{#cccccc}{\texttt{indefinitus}}} %等……等等，人家还没写呢/qq
\def{\Z}{\color{#ffffff}\colorbox{#114514}{\texttt{~NOI~level~}}} %Suruka's TODO.../qq
\def{\ex}{{^{\text{*}}}}
\newcommand{\note}[1]{{^{\tiny\color{gray}\texttt{#1}}}}
\newcommand{\bignote}[1]{{{\color{gray}\texttt{#1}}}}
\def{\wave}{\textasciitilde}
\newcommand{\subs}[2]{\color{ffffff}\colorbox{#1#177ff}{\texttt{~#2~}}}
\newcommand{\subss}[2]{\color{ffffff}\colorbox{#1#177ff}{\texttt{#2}}}
\newcommand{\nam}[1]{{\rescol\text{#1}}}
\newcommand{\unam}[1]{{\color{777777}\text{#1}}}

\rescol
\begin{array}{|c|}
\hline
\Large\kern{10.55em}\mathfrak{OI}~\textbf{知识清单}_{\color{321566}\mathfrak{Version:\beta0.8\kern{3.33em}\Large Author:~}\mathrm{\Large Suruka}}\\
\end{array}
\\

\begin{array}{|c|c|c|c|}
\hline
\textbf{知识点} & \textbf{类型} & \textbf{等级} & \textbf{掌握程度}\\
\hline
\unam{计算机基础与编程环境} & \ka & \subs{1}{1} & \U \\
\hline
\unam{C++ 语言基础} & \ka & \subss{1}{1\wave4} & \U \\
\hline
\unam{STL 基础} & \ka & \subss{3}{3\wave4} & \U \\
\hline
\nam{链表, List} & \kc & \subs{3}{3} & \U \\
\hline
\nam{栈, Stack} & \kc & \subs{3}{3} & \U \\
\hline
\nam{队列, Queue} & \kc & \subs{3}{3} & \U \\
\hline
\unam{树, Tree} & \kb & \subss{3}{3\wave4} & \U \\
\hline
\nam{（完全）二叉树, (Complete) Binary Tree} & \kb & \subss{3}{3\wave4} & \U \\
\hline
\nam{哈夫曼树, Huffman Tree} & \kb & \subs{4}{4} & \U \\
\hline
\unam{算法, Algorithm} & \km & \subss{1}{1\wave2} & \U \\
\hline
\nam{枚举, Enum} & \kn & \subs{1}{1} & \U \\
\hline
\nam{模拟, Simulation} & \kn & \subs{1}{1} & \U \\
\hline
\nam{贪心, Greedy Algorithm} & \kn & \subs{3}{3} & \U \\
\hline
\nam{递推, Iteration} & \kn & \subs{3}{3} & \U \\
\hline
\nam{递归, Recursion} & \kn & \subs{4}{4} & \U \\
\hline
\nam{二分, Dichotomy} & \kn & \subs{4}{4} & \U \\
\hline
\nam{倍增, Binary Lifting} & \kn & \subs{4}{4} & \U \\
\hline
\nam{高精度, Arbitrary-Precision Arithmetic} & \kn & \subs{4}{4} & \U \\
\hline
\nam{冒泡排序, Bubble Sort} & \kp & \subs{3}{3} & \U \\
\hline
\nam{简单选择排序, Simple Selection Sort} & \kp & \subs{3}{3} & \U \\
\hline
\nam{简单插入排序, Simple Insertion Sort} & \kp & \subs{3}{3} & \U \\
\hline
\unam{图, Graph} & \kg & \subss{3}{3\wave4} & \U \\
\hline
\nam{图的深度优先遍历, DFS of graphs} & \kg & \subs{4}{4} & \U \\
\hline
\nam{图的广度优先遍历, BFS of graphs} & \kg & \subs{4}{4} & \U \\
\hline
\nam{洪水填充算法, Floodfill Algorithm} & \kg & \subs{5}{5} & \U \\
\hline
\nam{线性动态规划, Linear Dynamic Programming} & \kf & \subs{4}{4} & \U \\
\hline
\nam{背包动态规划, Knapsack Dynamic Programming} & \kf & \subs{5}{5} & \U \\
\hline
\nam{区间动态规划, Interval Dynamic Programming} & \kf & \subs{5}{5} & \U \\
\hline
\unam{初中代数, Junior Algebra} & \kj & \subs{1}{1} & \U \\
\hline
\unam{初中平面几何, Junior Plane Geometry} & \kk & \subs{1}{1} & \U \\
\hline
\unam{进制, Base} & \kl & \subs{1}{1} & \U \\
\hline
\nam{格雷码, Gray Code} & \kl & \subs{2}{2} & \U \\
\hline
\unam{数论基础概念, Basic Concepts of Number Theory} & \kd & \subs{3}{3} & \U \\
\hline
\nam{欧几里得算法, Euclidean Algorithm} & \kd & \subs{3}{3} & \U \\
\hline
\nam{埃拉托斯特尼筛法, Sieve of Eratosthenes} & \kd & \subs{4}{4} & \U \\
\hline
\nam{线性筛法 / 欧拉筛法, Sieve of Euler} & \kd & \subs{4}{4} & \U \\
\hline
\unam{加法原理, Addition Principle} & \ki & \subs{2}{2} & \U \\
\hline
\unam{乘法原理, Multiplication Principle} & \ki & \subs{2}{2} & \U \\
\hline
\unam{排列组合, Permutation and Combination} & \ki & \subs{4}{4} & \U \\
\hline
\unam{杨辉三角, Pascal's Triangle} & \ki & \subs{4}{4} & \U \\
\hdashline
\hline
\hdashline
\unam{Linux 命令} & \ka & \subs{5}{5} & \U \\
\hline
\unam{Linux 编辑器} & \ka & \subs{5}{5} & \U \\
\hline
\unam{Linux 编译与调试} & \ka & \subs{5}{5} & \U \\
\hline
\unam{STL 拓展} & \ka & \subs{5}{5} & \U \\
\hline
\unam{类, Class} & \ka & \subs{6}{6} & \U \\
\hline
\nam{双端栈, Double-ended Stack} & \kc & \subs{5}{5} & \U \\
\hline
\nam{双端队列, Double-ended Queue} & \kc & \subs{5}{5} & \U \\
\hline
\nam{优先队列, Priority Queue}\note{[1]} & \kc & \subs{6}{6} & \U \\
\hline
\nam{倍增表 / ST 表, Sparse Table} & \kc & \subs{6}{6} & \U \\
\hline
\nam{哈希表, Hash Table} & \kc & \subs{6}{6} & \U \\
\hline
\nam{哈希函数, Hash Function} & \kl & \subss{5}{5\wave6} & \U \\
\hline
\nam{等价类, Equivalence Class} & \kl & \subs{6}{6} & \U \\
\hline
\nam{并查集, Disjoint-set Data Structure} & \kb & \subs{6}{6} & \U \\
\hline
\nam{树状数组, Binary Indexed Tree / Fenwick Tree} & \kb & \subs{6}{6} & \U \\
\hline
\nam{线段树, Segment Tree} & \kb & \subs{6}{6} & \U \\
\hline
\nam{笛卡尔树, Cartesian Tree} & \kb & \subs{7}{7} & \U \\
\hline
\nam{AVL 树, Adelson-Velsky and Landis Tree} & \kb & \subs{8}{8} & \U \\
\hline
\nam{树堆, Treap} & \kb & \subs{8}{8} & \U \\
\hline
\nam{伸展树, Splay} & \kb & \subs{8}{8} & \U \\
\hline
\nam{红黑树, Red Black Tree / Symmetric Binary B-tree} & \kb & \subs{8}{8} & \U \\
\hline
\nam{基环树, Pseudotree} & \kb & \subs{8}{8} & \U \\
\hline
\nam{稀疏图与稠密图, Sparse Graph and Dense Graph} & \kg & \subs{5}{5} & \U \\
\hline
\nam{孩子兄弟表示法, Binary Tree Notation} & \kg & \subs{6}{6} & \U \\
\hline
\nam{二分图, Bipartite Graph} & \kg & \subs{6}{6} & \U \\
\hline
\nam{欧拉图, Euler Graph} & \kg & \subs{6}{6} & \U \\
\hline
\nam{有向无环图, Directed Acyclic Graph} & \kg & \subs{6}{6} & \U \\
\hline
\nam{普里姆算法, Prim} & \kg & \subs{6}{6} & \U \\
\hline
\nam{克鲁斯克尔演算法, Kruskal} & \kg & \subs{6}{6} & \U \\
\hline
\nam{Boruvka, Borůvka's Algorithm}\ex & \kg & \subs{6}{6} & \U \\
\hline
\nam{戴克斯特拉算法, Dijkstra} & \kg & \subs{6}{6} & \U \\
\hline
\nam{贝尔曼-福特算法, Bellman-Ford Algorithm} & \kg & \subs{6}{6} & \U \\
\hline
\nam{最短路径快速算法, SPFA / Moore-Bellman-Ford Algorithm} & \kg & \subs{6}{6} & \U \\
\hline
\nam{弗洛伊德算法, Floyd-Warshall Algorithm} & \kg & \subs{6}{6} & \U \\
\hline
\nam{逐步插入回路法, Hierholzer} & \kg & \subs{6}{6} & \U \\
\hline
\nam{二分图判定, Bipartite Graph Check} & \kg & \subs{6}{6} & \U \\
\hline
\nam{最近公共祖先, Lowest Common Ancestor} & \kg & \subs{6}{6} & \U \\
\hline
\nam{拓扑排序, Topological Sorting of DAG} & \kg & \subs{6}{6} & \U \\
\hline
\nam{（强）连通图, (Strongly) Connected Graph} & \kg & \subs{7}{7} & \U \\
\hline
\nam{重连通图, Biconnected Graph} & \kg & \subs{7}{7} & \U \\
\hline
\nam{次小生成树, Subminimum Spanning Tree} & \kg & \subs{7}{7} & \U \\
\hline
\nam{单源次短路径, SSSSP} & \kg & \subs{7}{7} & \U \\
\hline
\nam{塔扬算法(3种), Tarjan(3 kinds)} & \kg & \subs{7}{7} & \U \\
\hline
\unam{时间复杂度分析, Time Complexity Analysis} & \km & \subs{6}{6} & \U \\
\hline
\unam{空间复杂度分析, Memory Complexity Analysis} & \km & \subs{6}{6} & \U \\
\hline
\nam{分治, Divide and Conquer} & \kn & \subs{6}{6} & \U \\
\hline
\nam{归并排序, Mergesort} & \kp & \subs{5}{5} & \U \\
\hline
\nam{快速排序, Quicksort} & \kp & \subs{5}{5} & \U \\
\hline
\nam{桶排序, Bucket Sort} & \kp & \subs{5}{5} & \U \\
\hline
\nam{堆排序, Heapsort} & \kp & \subs{6}{6} & \U \\
\hline
\nam{树形选择 / 锦标赛排序, Tournament / Tree Selection Sort} & \kp & \subs{6}{6} & \U \\
\hline
\nam{基数排序, Radix Sort} & \kp & \subs{6}{6} & \U \\
\hline
\nam{字符串哈希, String Hash}\note{[2]} & \ke & \subs{5}{5} & \U \\
\hline
\nam{KMP, Knuth-Morris-Pratt} \note{[2]} & \ke & \subs{6}{6} & \U \\
\hline
\nam{剪枝优化, Pruning} & \kh & \subs{6}{6} & \U \\
\hline
\nam{记忆化搜索, Memory Search} & \kh & \subs{6}{6} & \U \\
\hline
\nam{启发式搜索, Heuristically Search} & \kh & \subs{7}{7} & \U \\
\hline
\nam{双向宽度优先搜索, Bidirectional BFS} & \kh & \subs{7}{7} & \U \\
\hline
\nam{迭代加深搜索, Iterative Deepening DFS} & \kh & \subs{7}{7} & \U \\
\hline
\nam{搜索对象的压缩存储, Compressed Storage for Search Objects} & \kh & \subs{8}{8} & \U \\
\hline
\nam{树形动态规划, Tree Dynamic Programming} & \kf & \subs{6}{6} & \U \\
\hline
\nam{~状态压缩动态规划, State Compacting Dynamic Programming~} & \kf & \subs{7}{7} & \U \\
\hline
\nam{单调队列优化, Monotonic Queue Optimization} & \kf & \subs{8}{8} & \U \\
\hline
\nam{降低维度, Dimensionality Reduction} & \kf & \subs{8}{8} & \U \\
\hline
\nam{优先队列优化, Priority Queue Optimization} & \kf & \subs{8}{8} & \U \\
\hline
\nam{矩阵优化, Matrix Optimization} & \kf & \subs{8}{8} & \U \\
\hline
\nam{斜率优化, Slope Optimization} & \kf & \subs{8}{8} & \U \\
\hline
\nam{凸完全单调性, Convex Complete Monotonicity}\ex & \kf & \subs{8}{8} & \U \\
\hline
\nam{四边形不等式, Quadrilateral Inequality}\ex & \kf & \subs{8}{8} & \U \\
\hline
\nam{解析几何, Analytical Geometry} & \kk & \subs{6}{6} & \U \\
\hline
\nam{立体几何, Solid Geometry} & \kk & \subs{6}{6} & \U \\
\hline
\nam{同余式, Congruence Modulo} & \kd & \subs{5}{5} & \U \\
\hline
\nam{欧拉定理与欧拉函数, Euler's Theorem and Function} & \kd & \subs{7}{7} & \U \\
\hline
\nam{费马小定理, Fermat's Little Theorem} & \kd & \subs{7}{7} & \U \\
\hline
\nam{威尔逊定理, Wilson's Theorem} & \kd & \subs{7}{7} & \U \\
\hline
\nam{裴蜀定理, Bézout's Lemma} & \kd & \subs{7}{7} & \U \\
\hline
\nam{逆元, Inverse Element} & \kd & \subs{7}{7} & \U \\
\hline
\nam{扩展欧几里得算法, Extended Euclidean Algorithm} & \kd & \subs{7}{7} & \U \\
\hline
\nam{孙子定理 / 中国剩余定理, Chinese Remainder Theorem} & \kd & \subs{7}{7} & \U \\
\hline
\nam{可重集排列组合, Resettable Permutation and Combination} & \ki & \subs{6}{6} & \U \\
\hline
\nam{错排列与圆排列, Staggered and Circular Arrangement} & \ki & \subs{6}{6} & \U \\
\hline
\nam{鸽巢原理 / 抽屉原理, pigeonhole Principle / Drawer Principle} & \ki & \subs{6}{6} & \U \\
\hline
\nam{二项式定理, Binomial Theorem} & \ki & \subs{6}{6} & \U \\
\hline
\nam{容斥原理, Inclusion and Exclusion Principle} & \ki & \subs{7}{7} & \U \\
\hline
\nam{卡特兰数, Cattelan Number} & \ki & \subs{7}{7} & \U \\
\hline
\nam{矩阵, Matrix} & \kj & \subs{5}{5} & \U \\
\hline
\nam{稀疏, 三角, 对称矩阵, Sparse, Triangular, Symmetric Matrix} & \kj & \subs{6}{6} & \U \\
\hline
\nam{矩阵初等变换, Elementary Transformation of Matrix} & \kj & \subs{6}{6} & \U \\
\hline
\nam{矩阵基本运算, Matrix Basic Operations} & \kj & \subs{6}{6} & \U \\
\hline
\nam{高斯消元法, Gaussian Elimination} & \kj & \subs{7}{7} & \U \\
\hdashline
\hline
\hdashline
\nam{The author} & \kz & \subss{9}{o~n} & \Z
\end{array}
\\
\begin{array}{|c|}
\hdashline
\hline
\hdashline
\textbf{如果您也想获得~OI~知识清单，请前往~}\texttt{https://www.luogu.com.cn/paste/oz9xmtll}\kern{55pt}\\
\textbf{1. 版权声明}\kern{37.9em}\\
\textbf{本云剪贴板及其源代码与内容受~CC-BY-NC-ND~4.0~协议保护，即署名-非商业性使用-禁止演}\\
\textbf{绎~4.0~协议，使用者可以对本创作进行转载，但不得对本创作进行修改，亦不得依据本创作进行}\\
\textbf{再创作，不得将本创作运用于商业用途，具有法律效力。协议内容见下述网址：\kern{7.4em}}\\
\textbf{https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh\kern{12.7em}}\\
\textbf{如果您违反了该协议内容，将受到相关版权法的制裁。另请注意，您可以修改“掌握程度”一栏。}\\
\textbf{本云剪贴板及其源代码与内容还受~SATA~License~保护，即“点赞与感谢作者”许可证。使用者~~}\\
\textbf{使用本云剪贴板时，在遵守~CC-BY-NC-ND~4.0~协议的前提下，应马不停蹄的给本云剪贴板“点}\\
\textbf{赞”，并感谢作者即}\mathrm{Suruka}\textbf{。具体需要做的请参考许可证：www.luogu.com.cn/paste/t66h504j}\\
\textbf{2. 参考资料}\kern{37.9em}\\
\text{NOI~大纲}\note{[3]}\texttt{~-~https://www.noi.cn/upload/resources/file/2021/04/06/152179.pdf}\kern{3em}\\
\text{维基百科, Wikipedia}\texttt{~-~https://zh.wikipedia.org/}\kern{19.1em}\\
\textbf{3. 食用方法}\kern{37.9em}\\
GUGUGU\\
\textbf{4. 注释}\kern{40em}\\
\bignote{[1]:}\text{NOI 大纲上含有“有序队列”一项，疑为误笔。}\kern{20.5em}\\
\bignote{[2]:}\text{NOI 大纲上难度等级相反，疑为误笔。}\kern{23.5em}\\
\bignote{[3]:}\text{NOI 大纲版权声明不允许对其进行转载或修改，但本云剪贴板仅参考了该大纲，故不违例。}\kern{0.5em}\\
\hline
\end{array}
\\
$$
