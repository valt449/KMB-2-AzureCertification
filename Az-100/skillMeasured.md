<dl class="msl-body msl-accordion" id="question-types" role="tablist" aria-multiselectable="true"><dt role="presentation"><a
		 href="#syllabus-1" id="syllabus-1-label" role="tab" aria-controls="syllabus-1" aria-expanded="true" aria-selected="true"
		 class="selected"><span class="msl-accordion-icon x-hidden-focus icon-minus" tabindex="-1"></span>Manage Azure
			subscriptions and resources (15-20%)</a></dt>
	<dd id="syllabus-1" role="tabpanel" aria-expanded="true" aria-hidden="false" aria-labelledby="syllabus-1-label" style="display: block; position: relative; left: auto; right: auto;">
		<ul class="plain">
			<li class="x-hidden-focus">
				Manage Azure subscriptions
				<ul>
					<li class="x-hidden-focus"><i>May include but not limited to:</i> Assign administrator permissions; configure cost
						center quotas and tagging; configure Azure subscription policies at Azure subscription level</li>
				</ul>
			</li>
			<li class="x-hidden-focus">
				Analyze resource utilization and consumption
				<ul>
					<li class="x-hidden-focus"><i>May include but not limited to:</i> Configure diagnostic settings on resources;
						create baseline for resources; create and test alerts; analyze alerts across subscription; analyze metrics across
						subscription; create action groups; monitor for unused resources; monitor spend; report on spend; utilize Log
						Search query functions; view alerts in Log Analytics</li>
				</ul>
			</li>
			<li>
				Manage resource groups
				<ul>
					<li class="x-hidden-focus"><i class="x-hidden-focus">May include but not limited to:</i> Use Azure policies for
						resource groups; configure resource locks; configure resource policies; implement and set tagging on resource
						groups; move resources across resource groups; remove resource groups</li>
				</ul>
			</li>
		</ul>
	</dd><dt role="presentation"><a href="#syllabus-2" id="syllabus-2-label" role="tab" aria-controls="syllabus-2"
		 aria-expanded="true" aria-selected="true" class="selected"><span class="msl-accordion-icon icon-minus" tabindex="-1"></span>Implement
			and manage storage (20-25%)</a></dt>
	<dd id="syllabus-2" role="tabpanel" aria-expanded="true" aria-hidden="false" aria-labelledby="syllabus-2-label" style="display: block; position: relative; left: auto; right: auto;">
		<ul class="plain">
			<li>
				Create and configure storage accounts
				<ul>
					<li><i>May include but not limited to:</i> Configure network access to the storage account; create and configure
						storage account; generate shared access signature; install and use Azure Storage Explorer; manage access keys;
						monitor activity log by using Log Analytics; implement Azure storage replication</li>
				</ul>
			</li>
			<li>
				Import and export data to Azure
				<ul>
					<li><i>May include but not limited to:</i> Create export from Azure job; create import into Azure job; Use
						Azure Data Box; configure and use Azure blob storage; configure Azure content delivery network (CDN) endpoints</li>
				</ul>
			</li>
			<li>
				Configure Azure files
				<ul>
					<li><i>May include but not limited to:</i> Create Azure file share; create Azure File Sync service; create Azure
						sync group; troubleshoot Azure File Sync</li>
				</ul>
			</li>
			<li>
				Implement Azure backup
				<ul>
					<li><i>May include but not limited to:</i> Configure and review backup reports; perform backup operation; create
						Recovery Services Vault; create and configure backup policy; perform a restore operation</li>
				</ul>
			</li>
		</ul>
	</dd><dt role="presentation"><a href="#syllabus-3" id="syllabus-3-label" role="tab" aria-controls="syllabus-3"
		 aria-expanded="true" aria-selected="true" class="selected"><span class="msl-accordion-icon icon-minus" tabindex="-1"></span>Deploy
			and manage virtual machines (VMs) (20-25%)</a></dt>
	<dd id="syllabus-3" role="tabpanel" aria-expanded="true" aria-hidden="false" aria-labelledby="syllabus-3-label" style="display: block; position: relative; left: auto; right: auto;">
		<ul class="plain">
			<li>
				Create and configure a VM for Windows and Linux
				<ul>
					<li><i>May include but not limited to:</i> Configure high availability; configure monitoring, networking, storage,
						and virtual machine size; deploy and configure scale sets</li>
				</ul>
			</li>
			<li>
				Automate deployment of VMs
				<ul>
					<li><i>May include but not limited to:</i> Modify Azure Resource Manager (ARM) template; configure location of new
						VMs; configure VHD template; deploy from template; save a deployment as an ARM template; deploy Windows and Linux
						VMs</li>
				</ul>
			</li>
			<li>
				Manage Azure VM
				<ul>
					<li><i>May include but not limited to:</i> Add data discs; add network interfaces; automate configuration
						management by using PowerShell Desired State Configuration (DSC) and VM Agent by using custom script extensions;
						manage VM sizes; move VMs from one resource group to another; redeploy VMs</li>
				</ul>
			</li>
			<li>
				Manage VM backups
				<ul>
					<li><i>May include but not limited to:</i> Configure VM backup; define backup policies; implement backup policies;
						perform VM restore</li>
				</ul>
			</li>
		</ul>
	</dd>

## Assignments
* [x] Create github and azure account.
* [x] Install git and clone Github repository (checkout wednesdayOne branch)
* [x] Install VS code and the two extensions ('Markdown Preview Github Styling', 'Markdown Checkbox')
* [x] Create resource group from Azure cloud shell
* [x] Create VM Linux + Windows from Portal
* [x] Create VM Linux + Windows with Powershell
* [x] Create VM Linux + Windows from Azure CLI (or cloudshell)
* [ ] Install the Azure Workload components through the visual studio installer
* [ ] Create a new ressource group project and Find the 201-vm-copy-managed-disks from the azure samples github repository
* [ ] Create VM Linux + Windows with ARM template (use template from a already deployed vm and one from azure samples)
* [ ] Create managed disk seperately and create new VM where you attach the disk.
* [ ] Create VM availability-set and availability-zone (needs to be set when created) 
* [ ] Scale VM from portal and powershell or Azure CLI
* [ ] Create scale set
* [ ] Create multiple VM's with multiple subnets and a loadbalancer

* [ ] Host any webpage on Apache (linux) or IIS (Windows) and hit it from the web
* [ ] Create new assignements according to the learning objectives
* [x] Tear down resource group before you leave
* [x] Create pull request on github repository

##
<dt role="presentation"><a href="#syllabus-4" id="syllabus-4-label" role="tab" aria-controls="syllabus-4"
		 aria-expanded="true" aria-selected="true" class="selected"><span class="msl-accordion-icon icon-minus" tabindex="-1"></span>Configure
			and manage virtual networks (20-25%)</a></dt>
	<dd id="syllabus-4" role="tabpanel" aria-expanded="true" aria-hidden="false" aria-labelledby="syllabus-4-label" style="display: block; position: relative; left: auto; right: auto;">
		<ul class="plain">
			<li>
				Create connectivity between virtual networks
				<ul>
					<li><i>May include but not limited to:</i> Create and configure VNET peering; create and configure VNET to VNET;
						verify virtual network connectivity; create virtual network gateway</li>
				</ul>
			</li>
			<li>
				Implement and manage virtual networking
				<ul>
					<li><i>May include but not limited to:</i> Configure private and public IP addresses, network routes, network
						interface, subnets, and virtual network</li>
				</ul>
			</li>
			<li>
				Configure name resolution
				<ul>
					<li><i>May include but not limited to:</i> Configure Azure DNS; configure custom DNS settings; configure private
						and public DNS zones</li>
				</ul>
			</li>
			<li>
				Create and configure a Network Security Group (NSG)
				<ul>
					<li><i>May include but not limited to:</i> Create security rules; associate NSG to a subnet or network interface;
						identify required ports; evaluate effective security rules</li>
				</ul>
			</li>
		</ul>

## Assignments
* [ ] Create virtual gateway
* [ ] Create two VM on with a public ip adress and one without. Find a way to connect rdp/ssh to the one without a public ip address


	</dd><dt role="presentation"><a href="#syllabus-5" id="syllabus-5-label" role="tab" aria-controls="syllabus-5"
		 aria-expanded="true" aria-selected="true" class="selected"><span class="msl-accordion-icon icon-minus" tabindex="-1"></span>Manage
			identities (15-20%)</a></dt>
	<dd id="syllabus-5" role="tabpanel" aria-expanded="true" aria-hidden="false" aria-labelledby="syllabus-5-label" style="display: block; position: relative; left: auto; right: auto;">
		<ul class="plain">
			<li>
				Manage Azure Active Directory (AD)
				<ul>
					<li><i>May include but not limited to:</i> Add custom domains; configure Azure AD Identity Protection, Azure AD
						Join, and Enterprise State Roaming; configure self-service password reset; implement conditional access policies;
						manage multiple directories; perform an access review</li>
				</ul>
			</li>
			<li>
				Manage Azure AD objects (users, groups, and devices)
				<ul>
					<li><i>May include but not limited to:</i> Create users and groups; manage user and group properties; manage
						device settings; perform bulk user updates</li>
				</ul>
			</li>
			<li>
				Implement and manage hybrid identities
				<ul>
					<li><i>May include but not limited to:</i> Install and configure Azure AD Connect; configure federation and single
						sign-on; manage Azure AD Connect; manage password sync and writeback</li>
				</ul>
			</li>
		</ul>
	</dd>
</dl>
