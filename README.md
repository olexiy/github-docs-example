# GitHub Markdown examples inspired by Andrew Brown @ExamPro Terraform Bootcamp

## Using Codeblocks.

You can insert *codeblocks* into your .md files with three backticks at the beginning and the end of the codeblock - ```. 

- Not to be confused with quotation(')
- When you can, apply syntax highlighting to your codeblocks with the language name after top ticks. 

```hcl
Copy code
provider "aws" {
  region = "us-east-1"
}

resource "aws_s3_bucket" "my_bucket" {
  bucket = "my-unique-bucket-name"
  acl    = "private"

  tags = {
    Name        = "MyBucket"
    Environment = "Production"
  }
}
```
## Links and images
You can embed images into your documentation
<img src="/img/apple.png" />

