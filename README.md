# EDA Demo 🄯


## Getting Started

### 1 - Prerequisites

- python (adjust version in taskfile) - to create virtualenv.
- [task](https://github.com/go-task/task) - to execute taskfile.yml.
- docker - to spin eda container.

### 2 - Steps

```bash
$ git clone https://github.com/merou/event-driven-ansible.git
$ task run-eda
$ curl -X POST -H "Content-Type: application/json" \
       --data '{"playbook":"demo","task":"say_hello","name":"dani"}' \
       http://localhost:8080
```

