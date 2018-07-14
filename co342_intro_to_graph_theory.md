> dropped

## 1. Edge Connectivity

- __Definition:__ A graph $G$ is __k-edge-connected__ if $G-F$ is connected for any $F \subseteq E(G)$ where $|F| \leq k-1$. The __edge-connnectivity__ of $G$ is the largest $k$ for which $G$ is k-edge-connected, denoted $K'(G)$.
- __Lemma:__ For any graph $G$, $K'(G) \leq \delta(G)$ where $\delta(G)$ is the minum vertex degree.

## 2. Cuts and Bonds

- __Definition:__ Fir a set $S \subseteq V(G)$, the __cut induced__ by $S$ (or just a __cut__) is the set of all edges in $G$ with exactly one endpoint in $S$, denoted by $\delta_G(S)$, or $\delta(G)$. It is __noontrivial__ if $S \neq \varnothing$ and $S \neq V(G)$.
- __Lemma:__ if $F \in E(G)$ where $G-F$ is disconnected, then $F$ contained a cut in $G$, i.e. there exists $X \in V(G)$ where $\delta(X) \in F$.
- **Definition:** A __bond__ is a minimal non-empty cut.
- **Proposition:** Let $F=\delta(S)$ be a cut in a connected graph $G$. Then $F$ is a bond if and only if $G-F$ has exactly 2 opponents.
- **Definition:** The __symmetric difference__ of two sets $S$ and $T$ is $S \Delta T = (S \cup T) \backslash (S \cap T)$.
- **Lemma:** $\delta(S)\Delta \delta(T) = \delta(S \Delta T)$
- __Proposition:__ Every cut is a disjoint union of bonds.

## 3. Vertex Connectivity

- __Definition:__ A vertx $v$ is a __cut-vertex__ in $G$ if $G-v$ has more compoennts than $G$. A subset $S$ of vertices is a __separating set__ if $G-S$ is disconnected.
- __Definiton:__ A graph is __k-connted__ if it does not have a separating set of size at most $k-1$. The __connectivity__ of $G$ is the largest $k$ such that $G$ is k-connected, denoted $K(G)$.
- __Expansion Lemma:__ Let $G$ be a k-connected graph. Let $G'$ be obtained from $G$ by adding a new vertex $v$ that is joined to at least $k$ vertices in $G$. Then $G'$ is also k-connected.
- __Whiteney's Theorem:__ For any graph G, $K(G) \leq K'(G) \leq \delta(G)$.

## 4. Menger's Theorem

- __Definition:__ An __x, y-separating set__ is a set $S \subseteq V(G)\backslash {x, y}$ such that x, y are in different components of $G-S$. A set of x,y-paths are __internally-disjoint__ if no wo of them share any vertices other than x, y.

- __Menger's theorem (vertex version):__ Let x, y be two non-adjacent distinct vertices in $G$. Then the minimum size of an x, y-separating set is equal to the maximum number of a set of internally-disjoint x,-paths.

## 5. Corollaries of Menger's Theorem

- __Corollary:__ G is k-connected if and only if there exists k internally-disjoint x, y-paths for any distinct x, y $\in$ V(G).

- **Definition:** Let $X, Y \subseteq V(G)$. An __X, Y-separating set__ is a set of vertices S such that $G-S$ has no path from any vertex in X to any vertex in Y. A set of __disjoint X, Y-paths__ are paths that start with a vertex in X, end with a vertex in Y, no other vertices are in X nor Y, and no two paths share any vertices.

- __Menger's theorem (set version):__ Let X, Y $\subseteq$ V(G). Then the minimum size of an X, Y-separating set is equal to the maximum number of paths in a set of disjoint X, Y-paths.

- __Menger's theorem (edge version):__ Let x, y be two vertices in G. Then the minimum size of a cut that disconnected x from y is equal to the maximum number of paths in a set of edge-disjoint x, y-pths.

- __Definition:__ Let $G = (V, E)$. The __line graph__ of G is L(G), where the vertex set is $\{V_e | e \in E(G)\}$,and $v_e, v_f$ are adjacent in L(G) if and only if $e, f$ have a common endpoint in G.

- __Corollary:__ G is k-edge-connected if and only if there exist at least k edge-disjoint x, y-paths for any distinct x, y $\in$ V(G).

- __Definition:__ Let v be a vertex, X $\subseteq$ V(G) \ {V}. A __k-fan__ v to X is a set of k internally-disjoint paths that start in v, and with distinct vertices in X, and no internal vertices are in X.

- __Fan Lemma:__ Let G be k-connected, let v $\in​$ V(G), X $\subseteq​$ V(G) \ {v} where |x| $\geq​$ k. Then there exists a k-fan from v to X.

- __Corollary:__ Let G be k-connected where $k \geq 2$, and let x be a set of k vertices in G. Then there exists a cycle in G contains all vertices in X.

## 6. Structures of 2-connected Graphs

- __Theorem:__ For G with at least 3 vertices and $\delta(G) \geq 1$, the following are equivalent.

    1. G is 2-connected.
    2. For any distinct x, y $\in$ V(G), there is a cycle containing x and y.
    3. For any distinct $e, f \in E(G)$, there is a cycle contacting e and f.

## 7. Ear Decomposition

- __Definition:__ Let F be a subgraph of G. And __ear__ of F in G is a __nontrival__ path in G where only the two endpoints are in F. An __ear decomposition__ of G is a sequence of graphs $(G_0, G_1, …, G_k)$ where

  1. $G_0$ is a cycle in G;
  2. for $0 \leq i \leq k - 1$, $G_{i+1} = G_i + P_i$ where $P_i$ is an ear of $G_i$;
  3. $G_k = G$

- __Theorem:__ G is 2-connected if and only if G has an ear decomposition. Furthermore, any cycle in G can be $G_0$ in the ear decomposition, and any intermediate graph in the ear decomposition is 2-connected.

- __Proposition:__ If $(G_0, G_1, …, G_k)$ is an ear decomposition of $G$, then $k = |E(G)| - |V(G)|$.

## 8. Strong Orientation

- __Definition:__ An __orientation__ of G can e obtained by adding a direction for each edge uv, wither $u \rightarrow v$ or $v \rightarrow u$. A __directed u,v-walk__ has the form $u, v_1, …, v_k, v$ where $u \rightarrow v, v_1 \rightarrow v_2, …, v_k \rightarrow v$ are directed edges. A __strong orientation__ is one where there exists a directed u,v-walk for any ordered pair $u,v \in V(G)$.
- __Theorem:__ If G is 2-connected, then G has a strong orientation.

## 9. Blocks

- __Definition:__ A __block__ is a maximal connected nonempty subgraph that does not contain any cut-vertices.
- __Proposition:__ Each block is an induced subgraph.
- __Proposition:__ Vertices of a cycle must be in the same block.
- __Proposition:__ Two blocks share at most one vertex.
- __Proposition:__ A vertex in two or more blocks is a cut-vertex of G.
- __Definition:__ The block graph of G is a bipartite graph with bipartition (B, C) where B consists of vertices each representing a block of G, and C consists of all cut-vertices of G. For a block $b$ and a cut-vertex $v$, $bv$ is an edge if and only if $v$ is in block $b$ in G.
- __Proposition:__ The block graph is a forest.
- __Proposition:__ If u, v are in block B, then every u, v-path is in B.
- __Theorem:__ A connected graph has a strong orientation if and only if each of its blocks has a strong orientation.
- __Corollary:__ A graph has a strong orientation if and only if it is 2-edge-connected.

## 10. 3-connected Graphs

- __Definition:__ Let e be an edge in G. Then __contraction__ of e in G, denoted $G/e$, is the graph obtained from G by removing e and identifying the two endpoints of w.

- __Proposition:__ If X is a minimal separating set in G, then every vertex in X is adjacent to at least one vertex in each component.

- __Lemma:__ Let $k \geq 2$. If g is k-connected with at least k+2 vertices and $e = uv \in E(G)$ such that $G/e$ is not k-connected, then G has a separating set of size k that includes u and v.

- __Theorem:__ Let G be 3-connected with at least 5 vertices. Then G has an edge such that $G/e$ is 3-connected.

- __Corollary (Tutte's characterization of 3-connected graphs):__ A graph G is 3-connected if and only if there exists a sequence of graphs $G_0, G_1, G_2, …, G_k$ such that

  1. $G_0 = K_4$, $G_k = G$;
  2. for each $0 \leq i \leq k-1$, there exists an edge $xy \in G_{i+1}$ such that $\deg(x),\deg(y) \geq 3$ in $G_{i+1}$ and $G_i = G_{i+1}/e$.

- __Definition:__ A __wheel__ $w_n$ is a cycle of length n with another vertex joined to all vertices of the cycle.

- __Theorem (Tutte's Wheel Theorem): __ A graph G is a simple 3-connected graph if and only if there exists a sequence of simple graphs $G_0, G_1, …, G_k$ such that

  1. $G_0$ is a wheel, $G_k = G$;
  2. for $0 \leq i \leq k-1$, there is an edge $e \in G_{i+1}$ such that $G_i = G_{i+1} - e$ or $G_i = G_{i+1}/e$.

## 11. Vector Spaces for Graphs

- __Definition:__ The __edge space__ of G, denoted $\mathcal{E}(G)$, is the set of vectors of the form $GF(2)^{E(G)}$.

## 12. Cut Space

- __Definition:__ The cut space of G is the set of all cuts in G, denoted $C^*(G)$.

- __Proposition:__ $C^*(G)$ is a subspace of $\mathcal{E}(G)$.

- __Proposition:__ The set of all bonds span $C^*(G)$.

- __Definition:__ Let G be connected, let T be a spanning tree of G. For each $e \in E(T)$, $T-e$ has 2 components. let S be the vertices of one such component. Then $\delta_G(S)$ is a __fundamental cut__ in G, denoted by $D_e$ if $T$ is known.

- __Theorem:__ Let G be connected and let T be a spanning tree of G. Then the set of all fundamental cuts with respect to T is a basis for $C^*(G)$.

- __Corollary:__ If G is connected, then $\dim C^*(G) = |V(G)| -1$.

- __Corollary:__ If G has k components, then $\dim C^*(G) = |V(G)| -k$.

## 13. Cycle Space

- __Definition:__ The __cycle space__ of G is the subspace spanned by the cycles of G, denoted $C(G)$.
- __Definition:__ G is __even__ if every vertex has even degree.
- __Lemma:__ If $E_1, E_2$ are even, then $E_1 + E_2$ is even.
- __Theorem:__ Elements of the cycle space $C(G)$ are precisely the even subgraphs of G.
- __Definition:__ Let G be connected and T is a spanning tree in G. For any edge $e \in E(G)\backslash E(T)$, the unique cycle in $T+e$ is called a __fundemental cycle__, denoted $C_e$.
- __Corollary:__ If G is connected, then $\dim C(G) = |E(G)|-|V(G)| +1$.
- __Corollary:__ If G has k components, then $\dim \mathcal{C}(G) = |E(G)|-|V(G)| + k​$.

## 14. Orthogonal Complements

- __Definition:__ $F_1, F_2$ are __orthogonal__ if and only if $|F_1 \cap F_2|$ is even.
- __Theorem:__ $C^*(G)^{\bot} = C(G)$ and $C(G)^{\bot} = C^*(G)$.

## 15. Planar Graphs

- __Definition:__ A graph is __planar__ if it can be drawn on the plane so that edges only interact at common endpoints. The drawing is called a __planar embedding__. We call a planar embedding of a graph a __plane graph__. We use __points__ and __lines__ to refer to the representation of vertices and edges in the embedding, respectively.
- __Definition:__ A __curve__ is the continuous image of a closed unit line segment.
- __Definition:__ A __closed curve__ is the continuous image of a unit circle. An embedding of a cycle is a closed curve on the plane. A curve is simple if it does not intersect itself (i.e. mapping is 1-1).
- __Definition:__ A set of points is __arcwise-connected__ if any two of its points form the endpoints of a curve that is entirely in the set.
- __Jordan Curve Theorem:__ Any simple closed curve in the plane partitions the rest of the plane into two disjoint arcwise-connected open sets, one inside and one outside.
- __Definition:__ Given a simple closed curve $C$, the points inside is its **interior**, denote this open set by $int(C).$ The points outside is its **exterior**, denoted $ext(C)$. Together with $C$, we call them $Int(C)$ and $Ext(C)$ (closed sets).
- __Theorem:__ $K_5$ is not planar.
- __Theorem:__ $K_{3,3}$ is not planar.
- __Definition:__ A **subdivision** of $G$ is obtained from $G$ by replacing each edge with a new path of length at least 1 (i.e. introduce new vertices of degree 2 to the edges)
- **Proposition:** $G$ is planar if and only if every subdivision of $G$ is planar.
- **Corollary:** Any graph containing a subdivision of $K_5$ or $K_{3,3}$ is not planar.

## 16. Faces

- **Definition:** A **face** in a planar embedding is a maximal subset of points that are arcwise-connected and do not include any part of the embedding. Every planar embedding has one **unbounded face** or **outer face**. Each dace is **incident** with the vertices and edges on its boundary. Two faces are **adjacent** if they share at least one edge/line on their boundaries.
- **Theorem:** In a 2-connected plane graph $G$, each face is bounded by a cycle.
- __Proposition:__ The cycle space of a 2-connected plane graph $G$ is spanned by the set of all facial cycles of $G$.
- **Definition:** A **2-basis** of a subspace of $\mathcal{E}(G)$ is a basis $\mathcal{B}$ where each edge in $G$ is in at most 2 elements of $\mathcal{B}$.
- **Corollary:** In a 3-connected plane graph, all neighbours of a vertex lie on a common cycle.

## 17. Duals

- __Definition:__ Given a plane graph $G$, define the **dual** of $G$, denoted $G^*$, as follows: each face $f$ of $G$ corresponds to a vertex $f^*$ in $G^*$; for each edge of $G$ that has faces $f$ and $g$ on its two sides, there is a corresponding edge $e^*$ in $G^*$ that joins $f^*$ with $g^*$.
- **Proposition:** If $G$ is a plane graph, then $G^*$ is planar.
- **Proposition:** The dual of any plane graph is connected.
- **Proposition:** If $G$ is a connected plane graph, then $G = G^{**}$.
- **Proposition:** Let $G$ be a connected plane graph, and let $e \in E(G)$. If $e$ is not a cut-edge, then $(G-e)^*=G^*/e^*$. If $e$ is not a loop, then $(G/e)^*=G^*-e^*$.
- **Theorem:** Let $G​$ be a connected plane graph. If $C​$ is a cycle in $G​$, then $C^*​$ is a bond in $G^*​$. If $B​$ is a bond in $G​$, then $B^*​$ is a cycle in $G^*​$.
- **Corollary:** For a connected plane graph $G$, $\mathcal{C}(G) = \mathcal{C}^*(G^*)$ and $\mathcal{C}^*(G) = \mathcal{C}(G^*)$.

## 18. Abstract Duals

- __Definition:__ Let $G$ be a graph. Then $G^*$ is an **abstract dual** of $G$ if $G$ and $G^*$ have the same edge set, and the cycles of $G$ is equal to the bonds of $G^*$, and the bonds of $G$ is equal to the cycles of $G^*$.
- **Theorem:** If $G^*$ is an abstract dual of $G$, then $\mathcal{C}(G) = \mathcal{C}^*(G^*)$ and $\mathcal{C}^*(G) = \mathcal{C}(G^*)$. (connectedness is not required)
- **Corollary:** If $G^*$ is an abstract dual of $G$, then $G$ is an abstract dual of $G^*$.

## 19. Bridges

- **Definition:** Let $H$ be a subgraph of a connected graph $G$. A **bridge** of $H$ is either
  1. a component $J$ of $G-V(H)$ together with the edges in $\delta_G(V(H))$ and their endpoints; or
  2. an edge not in $H$ joining two vertices in $V(H)$. "trivial bridge"
- **Definition:** For a bridge $B$ of $H$, the vertices in both $B$ and $H$ are the **vertices of attachment**. The remaining vertices of $B$ are **internal** vertices. A bridge with $k$ $VOA$ is called a **k-bridge**. Two bridges with the same $VOA$ are **equivalent**.
- **Definition:** Let $C$ be a cycle. If a bridge has $k$ $VOA$, then they partition $C$ into $k$ **segments**. Two bridges **avoid** each other if the $VOA$ of one bridge is entirely within a segment of the other bridge. Otherwise they **overlay**. 
- **Definition:** Two bridges are **skew** if there is a sequence of distinct vertices $v_1, v_2, v_3, v_4$ on $C$ in cyclic order such that $v_1,v_3$ are the $VOA$ of one bridge, and $v_2,v_4$ are the $VOA$ of the other bridge.
- **Proposition:** Overlapping bridges of $C$ are either skew or equivalent 3-bridges.
- **Given plane graph $G$, cycle $C$:** Each bridge of $C$ is connected, so they are either in $Int(C)$or in $Ext(C)$, by the Jordan Curve Theorem. Bridges in $Int(C)$ are **inner** bridges, bridges in $Ext(C)$ are **outer** bridges.
- **Theorem:** If $G$ is a plane graph and $C$ is a cycle of $G$, then the inner (outer) bridges of $C$ avoid one another.
- **Definition:** In a subdivision, the **branch** vertices are the one of degree at least 3.

## 20. 3-connected planar graphs

- **Definition:** Two planner embeddings of $G$ are **equivalent** if they have the same sets of edges as face boundaries. A planar graph $G$ has a **unique embedding** if every embedding of $G$ is equivalent.
- **Definition:** A cycle $C$ is an **induced non-separating cycle** of $G$ if $C$ is an induced cycle and $G-V(C)$ is connected.
- **Theorem:** A cycle $C$ in a 3-connected plane graph $G$ is facial cycle if and only if $C$ is an induced non-separating cycle of $G$.
- **Corollary:** Every 3-connected planar graph has a unique embedding.
- **Corollary:** Every 3-connected planar graph has a unique dual graph.

## Kuratowski's Theorem

- **Definition:** We call subdivisions of $K_5$ and $K_{3,3}$ **Kuratowski subgraphs** (KS).

- **Theorem:** If $G$ is not planar, then $G$ contains a Kuratowski subgraph.

  

