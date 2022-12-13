
> KPLR Technologies uses mainly AWS Services as its cloud provider.

> Based on the fact That KPLR Technologies uses the cloud to provide Training environements for its students, you should be able 
to provide them on-demand and provide the instructors an excel file that contains all the necessary informations for students 
to access the training environments and practice their craft.

> The Instructors will provide you with specifications (number of instances, premade-configurations, type of instances ....) to which you 
will respond with the excel file described above

> There is mainly two types of enviornements we provide: Web Interfaced ubuntu Machines, and Amazon-Linux EC2 Instances

> The former is delivered through the AWS Console, yet, it's in the process of being delivered with CloudFormation.
Follow this link: [ubuntu-marketPlace](https://github.com/Nhaila-Abdessamad/CloudFormation/blob/main/ubuntu-marketPlace.md) to be able to launch these machines.

> The Latter is Delivered trhough CloudFormation, Follow These Instructions to be able to launch environements with CF.



## Steps to launch a stack

### Choose your region carefully
- In Case you didn't know, most aws resources are region-sensitive, for example AMIs that work In North-Veginea won't Work in Paris REGION
- That' why you have to choose the region and act based on it for what follows.
- In this Tutorial we will use North-Verginea as our REGION


### Open cloudformation in aws console (North-Verginea)
![ CloudFormation Landing Page](https://github.com/Nhaila-Abdessamad/CloudFormation/blob/main/Figs/CF%20Landing.png "Text to show on mouseover")


### Click Create stack (choose with new resources)

![ CloudFormation Landing Page](https://github.com/Nhaila-Abdessamad/CloudFormation/blob/main/Figs/create%20Stack.png "Text to show on mouseover")

### choose Upload template

### upload one of the templates provided in this repo

![ CloudFormation Landing Page](https://github.com/Nhaila-Abdessamad/CloudFormation/blob/main/Figs/Choose%20File.png "Text to show on mouseover")

### hit next


### give the stack a name and fill the parameters

![ CloudFormation Landing Page](https://github.com/Nhaila-Abdessamad/CloudFormation/blob/main/Figs/Stack%20Name%20and%20Parameters.png "Text to show on mouseover")

### next - next- Submit

