<p>
I decided to use VirtualBox, a type 2 hypervisor, for my VM set ups. If I had a second computer on hand I would attempt implementing a type 1 hypervisor but for now a type 2 will work. I am installing Kali Linux so I can do vulnerability testing on my home network.
</p>
<p>
After setting up VBox and installing Kali Linux I went into the VMs settings and alloted 4GB of ram and 2 CPU cores and left everything else on the default settings.
</p>
![4gb ram](/assets/images/4gbram.png)

![2CPU Cores](/assets/images/2cpu%20cores.png)

<p>
And now Kali Linux is fully set up on VirtualBox!
</p>

![Kali Linux Desktop](/assets/images/kali-linux%20setup.png)

<p>
I was having issues with Nmap giving false positives when doing a mass ping of my home network claiming that it discovered 256 active hosts when this definitely wasn't the case. I switched the network adapter from NAT to bridged and this solved the false positives issue!
</p>

![Vbox Bridged Adapter](/assets/images/bridgedadapter.png)

![Nmap Results](/assets/images/NMAP%20results.png)