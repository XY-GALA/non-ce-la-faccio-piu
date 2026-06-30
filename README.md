output "instance_id" {
  description = "ID della EC2 instance"
  value       = aws_instance.vm.id
}

output "instance_public_ip" {
  description = "IP pubblico della EC2 instance"
  value       = aws_instance.vm.public_ip
}

output "instance_private_ip" {
  description = "IP privato della EC2 instance"
  value       = aws_instance.vm.private_ip
}

output "security_group_id" {
  description = "ID del SG della EC2"
  value       = aws_security_group.vm.id
}

output "security_group_name" {
  description = "Nome SG della EC2"
  value       = aws_security_group.vm.name
}

output "key_pair_name" {
  description = "Nome key pair usata"
  value       = aws_key_pair.my_key.key_name
}
