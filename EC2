---

##  **EC2 (Elastic Compute Cloud)**

###  Describe EC2 Instances

```bash
aws ec2 describe-instances
```

###  Start an EC2 Instance

```bash
aws ec2 start-instances --instance-ids i-xxxxxxxxxxxxxxxxx
```

###  Stop an EC2 Instance

```bash
aws ec2 stop-instances --instance-ids i-xxxxxxxxxxxxxxxxx
```

###  Reboot an EC2 Instance

```bash
aws ec2 reboot-instances --instance-ids i-xxxxxxxxxxxxxxxxx
```

###  Terminate an EC2 Instance

```bash
aws ec2 terminate-instances --instance-ids i-xxxxxxxxxxxxxxxxx
```

###  Create a Key Pair

```bash
aws ec2 create-key-pair --key-name MyKeyPair
```

###  Describe Available AMIs

```bash
aws ec2 describe-images --owners amazon
```

###  Describe Security Groups

```bash
aws ec2 describe-security-groups
```

###  Allocate and Associate Elastic IP

```bash
aws ec2 allocate-address
aws ec2 associate-address --instance-id i-xxxxxxxxxxxxxxxxx --allocation-id eipalloc-xxxxxxxx
```

### Basic EC2 Instance Creation in Default VPC

```bash
aws ec2 run-instances \
  --image-id ami-0abcdef1234567890 \
  --instance-type t2.micro \
  --key-name MyKeyPair \
  --security-groups default \
  --count 1
```
