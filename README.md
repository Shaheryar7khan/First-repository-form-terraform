# first-repo-form-terraform
#My-first-automation-using-terraform.

//first automation of repository
provider "github" {
        token="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"
}

resource "github_repository" "terraform-first-repo" {
 name   = "First-repository-form-terraform"
 description    = "My-First-automation-using-terraform."
 visibility = "public"
 auto_init = true
}

