## HOW TO USE:
1. Copy the file to your $PATH folder, for example /usr/local/bin
2. Run "kubectl kubeplugin -t RESOURCE_TYPE -n NAMESAPCE
   where RESOURCE_TYPE is "node" or "pod" (default is "pod")
   and NAMESPACE - required namespace (default is "kube-system").
   both are optional.
3. Script will show CPU and Memory usage by resource. Break on press any key

### Demo:
![demo](https://github.com/vitali-o/AsciiArtify/blob/main/images/kubeplugin.gif?raw=true)