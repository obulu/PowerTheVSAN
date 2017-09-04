# PowerTheVSAN

This is for the VMWorld Hackathon Europe 2017 Team 5 for creating additional PowerShell / PowerCLI cmdlets to further improve the ability to monitor / manage vSAN environments. Born out of the idea that I have a few PS cmdlets already created and curious to know others challenges and how we can solve them. 

This should be made easier now that the vSAN API has been released and there is a new vSAN View for PowerCLI! More from William Lam (@lamw) here:
http://www.virtuallyghetto.com/2017/04/getting-started-wthe-new-powercli-6-5-1-get-vsanview-cmdlet.html



Get-VSANObjectHealth
- Obtains VSAN Health status of objects in VSAN Cluster. 
- Has choice of returning list of objects states, or a boolean result for object health
- Can force a refresh of the health data, or use the vCenter cached information
- Can show objects in each state if further troubleshooting is required
