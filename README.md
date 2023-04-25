# WaveLabs
Assignment

Wavelabs’ Lab setup consists of a network of n nodes, labeled from 1 to n.As a Network
Engineer, you are given times, a list of travel times as directed edges times[i] = (ui, vi, wi), where
ui is the source node, vi is the target node, and wi is the time it takes for a signal to travel from
source to target.
We will send a signal from a given node k. Return the minimum time it takes for all the n nodes
to receive the signal. If it is impossible for all the n nodes to receive the signal, return -1.
Example:

Input: times = [[2,1,1],[2,3,1],[3,4,1]], n = 4, k = 2
Output: 2

Constraints:
● 1 &lt;= k &lt;= n &lt;= 100
● 1 &lt;= times.length &lt;= 6000
● times[i].length == 3
● 1 &lt;= ui, vi &lt;= n
● ui != vi
● 0 &lt;= wi &lt;= 100
● All the pairs (ui, vi) are unique. (i.e., no multiple edges.)
