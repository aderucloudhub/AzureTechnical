1. **Reservations:** It will help us save the cost by committing to a 1- or 3-year term for specific resources like virtual machines, offering deep discounts over pay-as-you-go pricing.

   **Example:** running a D4s_v5 virtual machine 24/7 in East US for a production workload.
     By purchasing a 1-year Reserved Instance for that exact VM size and region, you can save up to 40–72% compared to pay-as-you-go pricing.
   
2. **Savings plan:** Azure Savings Plan offers up to 65% savings by committing to a fixed hourly spend for 1 or 3 years across eligible compute services, while allowing flexibility in VM sizes, regions, and types.

   **Example:** Instead of committing to a specific VM (like in reservations), you commit to spending $10/hour on compute.
     Azure will automatically apply the discount across any VM or eligible compute service you use—regardless of size, series, or region—until you reach your $10/hour commitment.
   
       
<img width="806" height="278" alt="diff savings plan vs reservations" src="https://github.com/user-attachments/assets/d632f045-d1ba-4621-9874-3dfdff8ac667" />

3. **Right sizing the workloads:** Continuously monitor resource utilization and adjust workload sizes as needed to ensure optimal performance and cost efficiency.
   
4. **unused resources decommissioning:** Regularly review your environment to identify unused or orphaned resources and establish a process for decommissioning them efficiently.
   
5. **Azure Hybrid Benefit with Software Assurance:** If you have existing licenses with Software Assurance (SA), you can apply them to your Azure workloads using the Azure Hybrid Benefit, which can reduce the total cost of        virtual machines by up to 50%.
   
6. **Auto Stop/Start VMs in non business hours:** For non-production workloads, we can implement auto start/stop for virtual machines during non-business hours, which can reduce costs by up to 50%.
     To further optimize savings, we can leverage Azure Reservations.
   
   **Example:**
     Consider a VM running on a D4s_v5 SKU (4 vCPUs, 16 GB RAM). By configuring it to automatically shut down during non-business hours (e.g., 12 hours overnight), we only incur charges for the remaining 12 hours of the day.
   
     To maximize cost efficiency, instead of reserving the full D4s_v5 instance, we can purchase a reservation for half the size, such as D2s_v5 (2 vCPUs, 8 GB RAM). Since the VM runs for only 12 hours, the D2s_v5                 reservation will be fully utilized twice each hour, effectively covering 24 hours of usage across the 12-hour window. This approach enables us to fully utilize the reservation and get the most out of our VM cost savings.

