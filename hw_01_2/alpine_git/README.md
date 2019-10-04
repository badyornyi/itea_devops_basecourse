Container clones git repository to current dir

Usage:
docker run --rm -e REPO_URL=<your_git_repo_url> -v $(pwd):/data/:rw alpine_git

eg:
docker run --rm -e REPO_URL=https://github.com/Dgadavin/devops-course-itea.git -v $(pwd):/data/:rw alpine_git
default REPO_URL:
https://github.com/badyornyi/itea_devops_basecourse.git
