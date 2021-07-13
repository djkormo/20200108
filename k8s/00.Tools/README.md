<img src="../../../img/logo.png" alt="Chmurowisko logo" width="200" align="right">
<br><br>
<br><br>
<br><br>

# Installing tools

## LAB Overview


1. Kubectl plugins

https://krew.sigs.k8s.io/docs/user-guide/setup/install/

```console
krew install krew
```

←[31;1mWARNING: ←[0mTo be able to run kubectl plugins, you need to add the
"%USERPROFILE%\.krew\bin" directory to your PATH environment variable
and restart your shell.



2. Octant

Octant is a browser-based UI aimed at application developers giving them visibility into how their application is running. I also think this tool can really benefit anyone using K8s, especially if you forget the various options to kubectl to inspect your K8s Cluster and/or workloads. Octant is also a VMware Open Source project and it is supported on Windows, Mac and Linux (including ARM) and runs locally on a system that has access to a K8S Cluster. After installing Octant, just type octant and it will start listening on localhost:7777 and you just launch your web browser to access the UI.

https://github.com/vmware-tanzu/octant/releases


3. Lens 

Lens an Electron-based desktop application that runs on Windows, Mac and Linux. Similar to Octant, it can connect to a local K8s Cluster and you can also add a custom configuration by copying/pasting the kube configuration which I thought was pretty nice. I thought the structure and layout was pretty easy to understand as I still found myself clicking around in Octant or scrolling on the left hand navigation which Lens did not have much of which is really nice. I think for a small number of K8s Cluster, Lens can be a nice option as you switch context by simply click on the icon in the far left. I think it can be a bit problematic if you need to manage a lot more and this is where I think Octant may have a better user experience with the drop down option.

https://k8slens.dev/



4. K9s

K9s is another terminal-based UI that actually came in as a recommendation from Fabian Brash after I shared on Twitter about Kubelive. I have to say, I am totally in love with K9s and its easy to interface. You get a similar experience like Kubelive with the ability to easily navigate through namespaces and pods. However, it is more than just navigating and something more practical that I was looking for which K9s provides is showing the logs of a specific pod. It is going to take me some time to memorize the various shortcuts as you can jump across different K8s objects by using ":" notation and specific key words like :ns for namespace and :po for pods as an example. K9s works just like Kubelive, you just type the command after installing the binary and it will give you access to the specific K8s Cluster which you have context in.

https://github.com/derailed/k9s/releases/



## END LAB

<br><br>

<center><p>&copy; 2021 Chmurowisko Sp. z o.o.<p></center>





