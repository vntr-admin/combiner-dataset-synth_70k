This was generated from the simple group model from Newman using the following parameters (Newman, Properties of highly clustered networks, 2003):

    70,000 vertices
    1500 groups
    Intra-group friendship probability (p) of 5.5%
    Group membership probability (s) of 0.22%

These numbers were chosen in part to have a group size of about 150, which has been experimentally found to be approximately the size of most true communities, known as the Dunbar Number (Gjoka, Kurant, Butts, & Markopoulou, 2010).


Formally, Newman's model consists of five parameters:

N: the number of vertices
M: the number of groups
p: the probability that two vertices within a given group are neighbors.
rm : A probability distribution that a vertex is in m groups.
sn: A probability distribution that a group contains n vertices.

We use the simplest probability distribution possible: that the probability any given user is in any given group is q.   Formally, this produces a binomial distribution for rm centered about qM, and another binomial distribution for sn centered about qN.


Newman, Mark EJ. "Properties of highly clustered networks." Physical Review E 68, no. 2 (2003): 026121.
