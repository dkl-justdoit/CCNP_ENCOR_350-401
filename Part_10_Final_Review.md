![image-20230704102940674](images/image-20230704102940674.png)

![image-20230704104647131](images/image-20230704104647131.png)

vManager - is the controller and cisco considers it the management plane 

vSmart - is the control plane. 

vEdge is the data plane. 

vBond is the orchestrator plane, and according to cisco it authenticates the vSmart controllers and the SD-WAN routers and orchestrates connectivity between them. 

It is the only device that must have a public IP address so that all SD-WAN devices in the network can connect to it. A vBond orchestrator is an SD-WAN router that only performs vBond orchestrator functions.

![image-20230704104940053](images/image-20230704104940053.png)

SD-Access Fabric Roles and Terminology Control Plane Node, Border Node, Edge Node, and other Fabric elements.

![image-20230704105346421](images/image-20230704105346421.png)

![image-20230704110400922](images/image-20230704110400922.png)

![image-20230704110946050](images/image-20230704110946050.png)

"Punt" is often used to describe the action of moving a packet from the fast path (CEF) to the route processor for handling. Cisco Express Forwarding (CEF) provides the ability to switch packets through a device in a very quick and efficient way while also keeping the load on the router‘s processor low. 

CEF is made up of two different main components: the Forwarding Information Base (FIB) and the Adjacency Table. Process switching is the slowest switching methods (compared to fast switching and Cisco Express Forwarding) because it must find a destination in the routing table. 

Process switching must also construct a new Layer 2 frame header for every packet. With process switching, when a packet comes in, the scheduler calls a process that examines the routing table, determines which interface the packet should be switched to and then switches the packet. The problem is, this happens for the every packet.

![image-20230704111722580](images/image-20230704111722580.png)

![image-20230704154421302](images/image-20230704154421302.png)

- onboard vEdge nodes into the SD-WAN fabric (vBond) 

- gather telemetry data from vEdge routers (vAnalytics) 

- distribute security information for tunnel establishment between vEdge routers (vSmart) - 
- manage, maintain, and gather configuration and status for nodes within the SD-WAN fabric (vManage)

![image-20230704154920081](images/image-20230704154920081.png)

![image-20230704155424243](images/image-20230704155424243.png)

![image-20230704160209241](images/image-20230704160209241.png)

![image-20230704160456534](images/image-20230704160456534.png)

![image-20230704161017583](images/image-20230704161017583.png)

![image-20230704184951732](images/image-20230704184951732.png)

![image-20230704185819600](images/image-20230704185819600.png)

![image-20230704190415938](images/image-20230704190415938.png)

![image-20230704190558438](images/image-20230704190558438.png)

![image-20230704190958782](images/image-20230704190958782.png)

![image-20230704192252065](images/image-20230704192252065.png)

![image-20230704192308654](images/image-20230704192308654.png)

![image-20230704194339664](images/image-20230704194339664.png)

![image-20230704194411115](images/image-20230704194411115.png)

![image-20230705111015731](images/image-20230705111015731.png)

![image-20230705111029935](images/image-20230705111029935.png)

![image-20230705112140246](images/image-20230705112140246.png)

![image-20230705112523269](images/image-20230705112523269.png)

![image-20230705125711608](images/image-20230705125711608.png)

![image-20230705130217350](images/image-20230705130217350.png)

![image-20230705130500884](images/image-20230705130500884.png)

![image-20230705130759512](images/image-20230705130759512.png)

![image-20230705131916968](images/image-20230705131916968.png)

![image-20230705134621749](images/image-20230705134621749.png)

![image-20230705135432720](images/image-20230705135432720.png)

Q89

![image-20230705140732651](images/image-20230705140732651.png)

![image-20230705154848971](images/image-20230705154848971.png)

![image-20230705203017511](images/image-20230705203017511.png)

Q168

![image-20230705215400831](images/image-20230705215400831.png)

![image-20230705222601102](images/image-20230705222601102.png)

Q139

![image-20230705223939557](images/image-20230705223939557.png)

![image-20230705225911877](images/image-20230705225911877.png)

Q119

![image-20230705231914139](images/image-20230705231914139.png)

![image-20230706092937707](images/image-20230706092937707.png)

![image-20230706093352464](images/image-20230706093352464.png)

![image-20230706093741259](images/image-20230706093741259.png)

![image-20230706094335431](images/image-20230706094335431.png)

![image-20230706094419322](images/image-20230706094419322.png)

![image-20230706101204186](images/image-20230706101204186.png)

![image-20230706105246088](images/image-20230706105246088.png)

![image-20230706110419120](images/image-20230706110419120.png)

![image-20230706110752966](images/image-20230706110752966.png)

![image-20230706111043832](images/image-20230706111043832.png)

![image-20230706140040895](images/image-20230706140040895.png)

![image-20230706140810493](images/image-20230706140810493.png)

![image-20230706141257037](images/image-20230706141257037.png)

Q259

![image-20230706144621393](images/image-20230706144621393.png)

![image-20230706144708669](images/image-20230706144708669.png)

![image-20230706145301992](images/image-20230706145301992.png)

Q253

![image-20230706153305987](images/image-20230706153305987.png)

![image-20230706153500827](images/image-20230706153500827.png)

![image-20230706153620340](images/image-20230706153620340.png)

![image-20230706154028773](images/image-20230706154028773.png)

![image-20230706160350590](images/image-20230706160350590.png)

![image-20230706162650626](images/image-20230706162650626.png)

![image-20230706165758086](images/image-20230706165758086.png)

![image-20230707120837811](images/image-20230707120837811.png)

![image-20230707121444968](images/image-20230707121444968.png)

![image-20230707123842532](images/image-20230707123842532.png)

![image-20230707125607144](images/image-20230707125607144.png)

Q381

Q380

Q360

![image-20230707152641468](images/image-20230707152641468.png)

![image-20230707154535506](images/image-20230707154535506.png)

![image-20230707160601947](images/image-20230707160601947.png)

![image-20230707161603358](images/image-20230707161603358.png)

![image-20230707162231919](images/image-20230707162231919.png)

![image-20230707165737624](images/image-20230707165737624.png)

![image-20230707171026865](images/image-20230707171026865.png)

![image-20230707172042982](images/image-20230707172042982.png)

![image-20230707172322318](images/image-20230707172322318.png)

![image-20230707174545186](images/image-20230707174545186.png)

  ![image-20230707174842491](images/image-20230707174842491.png)

![image-20230707175045020](images/image-20230707175045020.png)

![image-20230707175951371](images/image-20230707175951371.png)