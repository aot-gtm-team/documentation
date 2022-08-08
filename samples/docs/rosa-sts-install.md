---
sort: 3
---

# ROSA Quick installation with STS enabled

## Create Red Hat account


## Go to OCM 

### Create OCM roles.

create ocm-role

```
$ rosa create ocm-role --admin
I: Creating ocm role
? Role prefix: ManagedOpenShift
? Permissions boundary ARN (optional): 
? Role creation mode: auto
I: Creating role using 'arn:aws:iam::260702561168:user/yhanada@redhat.com-rhf009'
? Create the 'ManagedOpenShift-OCM-Role-13296330' role? Yes
I: Created role 'ManagedOpenShift-OCM-Role-13296330' with ARN 'arn:aws:iam::260702561168:role/ManagedOpenShift-OCM-Role-13296330'
I: Linking OCM role
? OCM Role ARN: arn:aws:iam::260702561168:role/ManagedOpenShift-OCM-Role-13296330
? Link the 'arn:aws:iam::260702561168:role/ManagedOpenShift-OCM-Role-13296330' role with organization '1cA88XNl8ao46OeY2u7sS3a3K9b'? Yes
I: Successfully linked role-arn 'arn:aws:iam::260702561168:role/ManagedOpenShift-OCM-Role-13296330' with organization account '1cA88XNl8ao46OeY2u7sS3a3K9b'
```

confirm com-role created

```
$ rosa list ocm-role
I: Fetching ocm roles
ROLE NAME                           ROLE ARN                                                           LINKED  ADMIN
ManagedOpenShift-OCM-Role-13296330  arn:aws:iam::260702561168:role/ManagedOpenShift-OCM-Role-13296330  Yes     Yes  
$
```
