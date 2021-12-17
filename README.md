## <font color='red'>Hitachi Vantara Customer Training </font>
The public Hitatchi Vantara Customer Success repository.

customer-training  
>  |-ansible   
>  |-ansible-tomcat

>  |-ldos-installation

#### How to checkout a folder
The Course-Materials are located under a folder, in asingle customer-training git repository; for example ansible, customer-training/dst/ansible.  You first need to download the index and then execute a sparse-checkout.  

For example - ansible

```
mkdir Course-Materials
cd Course-Materials
git clone --filter=blob:none --sparse https://github.com/hv-support/customer-training
cd customer-training
git sparse-checkout add ansible
cd dst
mv ansible ~/Course-Materials
```
* delete the empty customer-training folder.


##### Legal Stuff..    
<em>Materials made available by Hitachi Vantara via GitHub are provided for informational purposes without warranty of any kind.  Users must take full responsibility for the use and application of any such material.  In no event shall Hitachi Vantara be liable for any direct, indirect, special, consequential, or incidental damages, including without limitation, loss of profits arising out of the use of any such material, statements, information, and/or recommendations, even if Hitachi Vatnara has been advised of the possibility of such damages.</em> 
