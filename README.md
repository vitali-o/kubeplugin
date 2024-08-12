## HOW TO USE:
0. Rename scripts/kubeplugin to kubectl-kubeplugin.
1. Copy the file to your $PATH folder, for example /usr/local/bin
2. Run "kubectl kubeplugin -t RESOURCE_TYPE -n NAMESAPCE, where RESOURCE_TYPE is "node" or "pod" (default is "pod") and NAMESPACE - required namespace (default is "kube-system"). Both are optional.
3. Script will show CPU and Memory usage by resource. Break on press any key

Attention: nodes is a cluster-wide resources, so namespace is not shows in case of node monitoring.

### Demo:
![demo](https://github.com/vitali-o/kubeplugin/blob/main/images/kubeplugin.gif?raw=true)