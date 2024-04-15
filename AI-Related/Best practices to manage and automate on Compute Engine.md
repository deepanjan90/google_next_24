# Title:Best practices to manage and automate on Compute Engine
#### Date: 2024-04-10
#### URL: https://youtu.be/qnkqyNtqVnE



## SUMMARY

David Chang introduces a session on managing large fleets of VMs on Google Cloud, featuring insights from Omar Suram, Milo Harris, and Mohammad Al Hereri on automation, governance, and best practices.

## IDEAS:

- Managing large fleets of VMs presents challenges in modernization, agility, and enforcing organizational controls.
- Google Cloud offers tools for customers at any stage of their modernization journey, from VM management to full automation.
- Core Logic's journey involved migrating over 10,000 servers to GCP, focusing on automation and security.
- ATB Financial's approach included using spot instances for cost savings and automating deployments for consistency.
- Infrastructure as Code (IaC) ensures consistent and standardized deployments across Google Cloud projects.
- Repaving servers instead of patching can improve security and system resilience.
- Customizing Google Cloud's golden images helps meet specific security and compliance requirements.
- VM Manager and OS Inventory tools facilitate large-scale VM fleet management and security patching.
- Workload Manager allows continuous validation of specialized workloads against Google's best practices.
- Custom rules in Workload Manager enable organizations to automate their governance policies.
- Architecture Center provides a one-stop solution for best practices, guides, and blueprints on Google Cloud.
- Automating the deployment of assets reduces manual work and increases operational efficiency.
- FinOps teams play a crucial role in managing cloud costs and ensuring efficient use of cloud resources.
- Collaboration with Google Cloud account managers can provide access to new tools and shared expertise.
- The "crawl, walk, run" approach helps organizations gradually adopt cloud practices and improve over time.
- Challenging legacy processes can unlock efficiencies and better utilize modern cloud capabilities.
- Establishing a Cloud Operating Model (COM) is key to successful cloud migration and management.
- Shared Terraform modules and CI/CD pipelines standardize infrastructure deployment across teams.
- The repave model for OS updates eliminates the need for manual patching and enhances security.
- Locking down projects to use approved OS images ensures compliance with security standards.
- Real-time monitoring and labels help manage security compliance and optimize resource usage.
- Engaging with Google Cloud for roadmap sessions can influence product development to meet customer needs.

## INSIGHTS:

- Automation and standardization are critical for managing large VM fleets efficiently on Google Cloud.
- Transitioning to cloud requires reevaluating legacy processes to leverage modern cloud capabilities fully.
- Infrastructure as Code (IaC) not only standardizes deployments but also embeds security and compliance by design.
- The repave model represents a shift in managing OS updates, prioritizing automation over manual intervention.
- Collaborative partnerships with cloud providers can accelerate innovation and adoption of best practices.
- FinOps teams are essential in optimizing cloud costs through real-time monitoring and strategic resource allocation.
- The "crawl, walk, run" methodology allows organizations to evolve their cloud maturity at a manageable pace.
- Customizing cloud governance policies through tools like Workload Manager aligns with organizational needs while ensuring best practices.
- Engaging with cloud account managers opens opportunities for tailored support and access to cutting-edge tools.
- Establishing a Cloud Operating Model (COM) provides a comprehensive framework for successful cloud migration and management.

## QUOTES:

- "Managing large fleets of VMs can be challenging."
- "Google Cloud offers tools for customers at any stage of their modernization journey."
- "Infrastructure as Code ensures consistent and standardized deployments."
- "Repaving servers instead of patching improves security."
- "Custom rules in Workload Manager enable organizations to automate governance policies."
- "Architecture Center provides best practices, guides, and blueprints on Google Cloud."
- "Automating asset deployment reduces manual work and increases efficiency."
- "FinOps teams ensure efficient use of cloud resources."
- "Collaboration with Google Cloud account managers provides access to new tools."
- "The 'crawl, walk, run' approach helps organizations gradually adopt cloud practices."
- "Challenging legacy processes can unlock efficiencies in the cloud."
- "Shared Terraform modules standardize infrastructure deployment across teams."
- "The repave model for OS updates eliminates the need for manual patching."
- "Locking down projects to use approved OS images ensures compliance."
- "Real-time monitoring helps manage security compliance and optimize resource usage."
- "Engaging with Google Cloud for roadmap sessions can influence product development."

## HABITS:

- Regularly evaluating cloud management practices for improvements.
- Using Infrastructure as Code for consistent deployments across projects.
- Implementing repaving instead of patching for OS updates.
- Customizing golden images to meet specific security requirements.
- Utilizing VM Manager and OS Inventory for fleet management.
- Continuously validating workloads against best practices with Workload Manager.
- Leveraging Architecture Center for guidance on Google Cloud deployments.
- Automating asset deployment to reduce manual interventions.
- Establishing FinOps teams to manage cloud costs efficiently.
- Collaborating with Google Cloud account managers for tailored support.
- Adopting a "crawl, walk, run" approach to evolve cloud maturity.
- Challenging legacy processes to better utilize modern cloud capabilities.
- Standardizing infrastructure deployment with shared Terraform modules.
- Ensuring all compute deployments are fully automated for security improvements.
- Locking down projects to use only approved OS images for compliance.

## FACTS:

- Core Logic migrated over 10,000 servers to GCP in a five-year journey focusing on automation and security.
- ATB Financial runs a large hybrid environment with 550 compute engines and 400 GKE clusters on GCP.
- Google Cloud's VM Manager facilitates large-scale VM fleet management and security patching.
- Workload Manager allows continuous validation of specialized workloads against Google's best practices.
- Architecture Center offers a one-stop solution for best practices, guides, and blueprints on Google Cloud.
- The repave model eliminates the task of OS patching from support teams, focusing on application support instead.
- Core Logic established an image factory dedicated to producing golden images based on Google's official GCE public images.
- ATB Financial's FinOps team works with technical teams to ensure efficient use of GCP assets.

## REFERENCES:

- Google Cloud's VM Manager
- Workload Manager
- Architecture Center
- Terraform
- Ansible
- Jenkins CI/CD pipelines
- GCP Python SDK
- Google's official GCE public images
- BigQuery
- Looker

## RECOMMENDATIONS:

- Adopt Infrastructure as Code for consistent, secure deployments across Google Cloud projects.
- Consider repaving over patching for OS updates to enhance security and system resilience.
- Customize golden images to meet specific security and compliance requirements efficiently.
- Utilize VM Manager and OS Inventory tools for effective large-scale VM fleet management.
- Validate specialized workloads continuously against best practices with Workload Manager.
- Leverage Architecture Center for comprehensive guidance on deploying on Google Cloud.
- Automate asset deployment to reduce manual work and increase operational efficiency significantly.
- Establish FinOps teams to optimize cloud costs through strategic resource allocation and monitoring.
- Engage with Google Cloud account managers for access to new tools and shared expertise beneficially.
- Implement a "crawl, walk, run" methodology to manageably evolve your organization's cloud maturity.