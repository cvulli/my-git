vars = {
      "base_url" : "git@gitlab.com:chaitanya.vulli/my-git.git",

        "gitlab_destination" : "gitlab",
        "gitlab_url" : "/external/my-git.git",
        "gitlab_revision" : "c5c370ba65550f01c769ab4c08c3b76cc0c2b36e",
}

deps = {
      Var("gitlab_destination") :
            Var("base_url") + "@" + Var("gitlab_revision")
}
