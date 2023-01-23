# CT - Lab AWS EC2 Image Builder

Repositório Criado Para Lab do Serviço da AWS EC2 Image Builder

## Passo a Passo da Instalação

### 1 - Crie Uma Conta AWS
  
*  https://aws.amazon.com/pt/getting-started/guides/setup-environment/module-one/

### 2 - Crie uma VPC Padrão na AWS

*    https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/default-vpc.html#create-default-vpc

### 3 - Execute as Stacks de CloudFormation e Componentes Disponíveis Nesse Repositório e Se Divirta

*  [AutoScallinGroup](./CloudFormation/AutoScallingGroup/cf-asg-ec2-image-builder-amazon-linux-2.yaml)
*  [EC2ImageBuilder](./CloudFormation/EC2ImageBuilder/cf-ec2-image-builder-linux-amazon-linux-2.yml)
*  [BuildComponets-Wordpress](./Components/install_wordpress.yml)
*  [BuildComponets-Wordpress+DB](./Components/install_wordpress_with_db.yml)

### Links Úteis

* [Workshop EC2 Image Builder](https://ec2-image-builder.workshop.aws/)
* [Workshop Studio EC2 Image Builder](https://catalog.us-east-1.prod.workshops.aws/workshops/d6c7ecdc-c75f-4ad1-910f-fdd994cc4aed/en-US/100-ec2-ib)
* [Amazon EC2 Image Builder](https://aws.amazon.com/image-builder/)
* [AWS Cloud Development Kit (CDK)](https://docs.aws.amazon.com/cdk/index.html)
* [EC2 Image Builder Documentation](https://docs.aws.amazon.com/imagebuilder/)
  * [EC2 Image Builder User Guide](https://docs.aws.amazon.com/imagebuilder/latest/userguide/index.html)
  * [EC2 Image Builder API Reference](https://docs.aws.amazon.com/imagebuilder/latest/APIReference/index.html)
  * [EC2 Image Builder CLI Reference](https://docs.aws.amazon.com/cli/latest/reference/imagebuilder/index.html)
  * [EC2 Image Builder CloudFormation Reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_ImageBuilder.html)
  * [CIS Hardening Components for EC2 Image Builder ](https://cisecurity.atlassian.net/servicedesk/customer/portal/15/article/2850881850)

### Blogs

* [Automate OS Image Build Pipelines with EC2 Image Builder](https://aws.amazon.com/blogs/aws/automate-os-image-build-pipelines-with-ec2-image-builder/) (02 December 2019)
* [Executing Ansible playbooks in your Amazon EC2 Image Builder pipeline](https://aws.amazon.com/blogs/compute/executing-ansible-playbooks-in-your-amazon-ec2-image-builder-pipeline/) (08 July 2020)
* [Create immutable servers using EC2 Image Builder and AWS CodePipeline](https://aws.amazon.com/blogs/mt/create-immutable-servers-using-ec2-image-builder-aws-codepipeline/) (07 January 2021)
