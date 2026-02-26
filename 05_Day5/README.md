Create GP3 Volumn
--
Why : AWS introduced gp3 volumes (General Purpose SSD) to provide a more flexible, cost-effective storage option, 
offering 20% lower cost per GB than gp2 and allowing independent scaling of IOPS and throughput from storage capacity

Implementation checklist :
1) Login to AWS EC2 console.
2) Under Elastic block Store, click volumn.
3) Configure Volumn.
4) Add Name tag.
5) Click Create volumn.

Note :
gp3 eliminates the need to pay for extra,
unused capacity just to gain higher IOPS or throughput, offering better performance-per-dollar
