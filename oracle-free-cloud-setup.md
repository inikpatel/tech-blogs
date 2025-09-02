\# How I Got a Free, Powerful Cloud Server for Life



\*Image created by AI by the author\*



If you’ve ever wished for your own \*\*4 CPU, 24 GB RAM, and 200 GB storage\*\* cloud server without paying a cent, here’s how to do it.  



Oracle Cloud’s \*\*Always Free tier\*\* offers a server powerful enough to build, test, and host applications long-term.  



---



\## Why You’d Want This



Perfect for:  

\- Students experimenting with new tech  

\- Developers testing apps  

\- Cloud/DevOps engineers running pipelines  

\- Hobbyists learning Linux or server administration  



---



\## What You Get (Always Free)



\- 4 CPU cores  

\- 24 GB RAM  

\- 200 GB block storage  

\- Choice of Linux distributions (Ubuntu, Oracle Linux, CentOS, etc.)  

\- Load balancing, networking, and more  



You can run:  

\- APIs \& backend services  

\- Databases (Postgres, MySQL, etc.)  

\- Demo/learning apps  

\- Automation pipelines  

\- Side projects  



---



\## Step 1: Sign Up



1\. Go to \[Oracle Cloud Free Tier](https://www.oracle.com/cloud/free/)  

2\. Enter your email and details  

3\. Add a credit card (verification only; no charges if you stay in the free tier)  

4\. Confirm and log in  



\*\*Tip:\*\* Choose a region that supports Ampere ARM-based VMs, e.g., `us-ashburn-1`, `us-chicago-1`, `us-sanjose-1`.



---



\## Step 2: Create Your Free VM



1\. Open \*\*Compute → Create Instance\*\*  

2\. Pick your OS (Ubuntu recommended)  

3\. Select the \*\*Always Free ARM Ampere shape\*\* (4 OCPUs, 24 GB RAM)  

4\. Launch your VM  



📖 Full guide: \[Oracle Docs Tutorial](https://docs.oracle.com/en-us/iaas/Content/Compute/tutorials/first-linux-instance/overview.htm)  



---



\## Step 2.1: Add Free Block Storage



1\. Go to \*\*Block Storage → Create Block Volume\*\*  

2\. Choose size (up to 200 GB Always Free)  

3\. Attach the block volume to your VM  

4\. Log in and format/mount the volume  



---



\## Step 3: Connect to Your VM



Upload or generate an SSH key during instance creation. Then:



```bash

ssh -i your\_key.pem ubuntu@your\_instance\_ip



---



\## Things to Know


Architecture: It’s ARM-based. Most software works fine, but double-check if you rely on niche packages.



Limits: Stick to Always Free shapes or you’ll be charged.



Inactivity: Log in regularly; Oracle can reclaim idle instances.



---



\## What If You Get an “Out of Capacity” Error?



These free servers are popular, so you might see this error. Options:



Retry later: Capacity frees up as others delete servers.



Switch to Pay-As-You-Go: Even then, the Always Free instances remain free, but you’ll get priority.



Automate the check: Advanced users can script capacity checks and auto-create servers. Explained in detail here: YouTube Tutorial.



⚠️ Pro Tip: Set a budget alert for $1 so you’ll know if something non-free gets created.


---



\## Final Thoughts



A server with 4 CPUs and 24 GB RAM, free forever, is something AWS, Azure, and Google Cloud don’t offer.



Oracle Cloud’s Always Free tier is a hidden gem for anyone who wants to learn, experiment, or host real projects.



It’s safe, reliable, and best of all—free for life if you stay within limits.



Thanks for reading 🙏👏

