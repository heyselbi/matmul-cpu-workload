# matmul-cpu-workload


"Memory requests and limits are associated with Containers, but it
is useful to think of a Pod as having a memory request and
limit. The memory request for the Pod is the sum of the memory
requests for all the Containers in the Pod. Likewise, the memory
limit for the Pod is the sum of the limits of all the Containers
in the Pod.

Pod scheduling is based on requests. A Pod is scheduled to run on
a Node only if the Node has enough available memory to satisfy
the Pod’s memory request."

Link: https://kubernetes.io/docs/tasks/configure-pod-container/assign-memory-resource/#specify-a-memory-request-that-is-too-big-for-your-nodes
