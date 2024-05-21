# jamf-site-counts

This script pulls the device counts from each site in a Jamf instance. This script currently does not handle finding devices not in a site, but that is something that would probably be useful to include.

## Operation

Enter credentials for an account with Full Jamf Pro access. It just needs read access. Run the script to get a CSV file that has each site count with columns for Computers, Mobile Devices, and Apple TVs.

## Jamf Product Issue

My instance was affected by a PI where there were stale records. Some site counts were off by as many as 20 computers. Jamf Support is able to resolve this, and they told me that this is a resolved PI, so once support cleans up the bad records there is no issue with them returning.
