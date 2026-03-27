# prometheus-and-grafana

This is based off the DevOps Roadmap Project [Prometheus And Grafana](https://roadmap.sh/projects/monitoring)

Setup monitoring using Prometheus and visualize metrics in Grafana.

This is from [DevOps Projects](https://roadmap.sh/devops/projects) as per roadmap.sh

## Description From Site 

The goal of this project is to implement a comprehensive monitoring system for your server infrastructure using Prometheus for metric collection and Grafana for visualization. This setup will provide real-time insights into your server's performance, resource utilization, and overall health.

This project will provide you with hands-on experience in setting up a production-grade monitoring system. You'll gain valuable skills in metric collection, data visualization, and system observability, which are crucial for maintaining reliable and performant infrastructure.

## Requirements

To begin this project, you'll need:

- [X] A running server to monitor. You can use an existing server from a previous project or setup a new server on Digital Ocean or another cloud provider

- [X] An application running on the server using some dependencies e.g., Nginx, Node.js, or others.

Once your server is operational, you'll proceed with setting up Prometheus and Grafana.

### Prometheus Setup 

Prometheus is a powerful, open-source monitoring and alerting toolkit. Follow these steps to set it up:

- [ ] Install Prometheus on your server

- [ ] Configure prometheus for scarping intervals, endpoints and retention policies

- [ ] Install and configure exporters for System metrics (CPU, memory, disk, network). Also setup additional exporters for services like Nginx, MySQL, MongoDB, etc.

- [ ] Implement custom exporters or instrumentation for application-specific metrics

Prometheus offers extensive data collection capabilities and a flexible query language (PromQL) for data analysis.

### Grafana Configuration

Grafana provides customizable dashboards for your metrics. You can setup a dashboard for system metrics and another for application metrics. Follow these steps:

- [ ] Install Grafana on your server

- [ ] Connect Grafana to Prometheus as a data source

- [ ] Create dashboards for various metrics:

    - [ ] System overview (CPU, memory, disk, network)

    - [ ] Application-specific metrics

    - [ ] Custom panels using PromQL queries

- [ ] Set up user authentication and authorization for your Grafana instance

### Advanced Goals 

For those looking to expand their skills and create a more robust monitoring system, consider implementing these advanced features:

- [ ] Set up alerting rules in Prometheus and configure notification channels in Grafana (e.g., email, Slack)

- [ ] Implement Prometheus recording rules to optimize query performance

- [ ] Use Prometheus service discovery for automatic monitoring of dynamic environments

- [ ] Integrate log aggregation using Loki and correlate logs with metrics in Grafana

- [ ] Create a custom exporter for a specific application or service you're running


## prerequisites

- Setup the following repository secrets:
    - DO_TOKEN : Digital Ocean access token
    - DO_SPACES_SECRET_KEY : Digital Ocean spaces secret key (for Terraform state file)
    - DO_SPACES_ACCESS_KEY : Digital Ocean spaces access key (for Terraform state file)
    - DO_SSH_PUBLIC_KEY : Keypair to be used for VM 
    - DO_SSH_PRIVATE_KEY : Keypair to be used for VM

## To Run  

- Run workflow 


## Notes 

- Notes

## Lessons Learned

- Lessons