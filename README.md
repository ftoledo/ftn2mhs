# ftn2mhs v0.0.1
Gate Fidonet Style messages (FTN) to MHS Worldgroup BBS

There is a bash scripts that process fidonet packets and import/export into Worldgroup Server MHS gateway
as SMF-70 message format.

This is a prof of concept to learn and understand how to WG import messages to forums and user emails
and try to get fidonet into WG.

It's still early develpoment and should not used on production environments

I think that sometime i will code it in more environment-friendly for WG (win32) that be native,
maybe WG module too. But i like the multiplatform style. I'm gnu/linux user.

## ToDo

 [ ] Validate packet address when import, to prevent get packets for other nodes
 [ ] Validate user/forum name/existence in WG (if posible)
 [ ] Packet pasrod support?
 [ ] unified loggin file and detailed log
 [ ] Organice config file options
 [ ] Create hooks (pre/post for import/export)
 [ ] Vault directory for failed process packets
 [ ] Map file for areas (if echomail name differs from WG Forum name)
 [ ] Use real names instead of user-id
 [ ] Support for bounced messages for errors/invalid processing
 [ ] Support locale/i18n
