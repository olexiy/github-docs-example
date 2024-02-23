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

## Tasklists in Github

Github extends Markdown to have a list where you can check of items. <sup>[1]</sup>

- [ ] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

- [x] task allready done
- [ ] open task
- [ ] #1 Link to issue

## Tables
We can also make a table


## Extra pop
- We can use emojies in markup<sup>[2]</sup> :brain:

# Reference
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

- [GFM - Task List ](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [Emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)<sup>[2]</sup>
