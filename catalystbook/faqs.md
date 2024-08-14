# Frequently Asked Questions

This page addresses the most commonly asked questions about The Catalyst Project.

## Getting Started

### When can I start using the hub?

You can use the hub as soon as it is deployed! Please see the [List of Hubs](./current-community-partners.md#list-of-hubs) to find the URL of your hub.

### How do I get started with the hub?

Please take the [Hub Champion Training](https://catalystproject.cloud/hub-champion-training/) course for an introduction to administering your hub for your community.

### What can I use the hub for?

Take look at the [learner profiles](https://catalystproject.cloud/hub-champion-training/profiles/learner-profiles.html) of the Hub Champion Training for an idea of what to use the hub for, or browse the [2i2c website](https://2i2c.org/) for inspiration.

### Who can access the hub?

Any collaborator or learner associated with your institution can use the hub for research and education purposes, even if they are not affiliated with The Catalyst Project.

### How long is the service available for?

Funding from CZI is currently available until November 2025. Get in touch with us if you would like to work with us to explore funding opportunities.

### What happens to my data after the service ends?

The Catalyst Project will confirm with you before any data is deleted from your hub. If you would like to migrate your data, then this can be arranged. See the [2i2c Infrastructure Guide](https://infrastructure.2i2c.org/hub-deployment-guide/hubs/delete-hub/) for details on how a hub is decommissioned and our [Privacy Policy](privacy.md) for how The Catalyst Project generally manages data.

## Best Practises

### Can I store sensitive data, such as health records and patient information, on the hub?

No, we do not recommend that you store sensitive data on the hub for security reasons. Data must be handled according to local regulatory and legal frameworks. Consider engaging with others to help you define policies, processes and systems for working safely with sensitive data. See [The Turing Way – Sensitive Data Projects](https://book.the-turing-way.org/project-design/sdp) for an overview of managing sensitive research data.

### What training is available for using the hub?

Take a look at our [Training](training.md) page for a comprehensive list of training provided by The Catalyst Project.

## Technical Questions

### What is meant by cloud infrastructure?

Cloud infrastructure refers to the hardware and software components to provide a cloud computing environment. In the case of The Catalyst Project, this means the infrastructure used to deliver an interactive computing platform. See the [2i2c website](https://2i2c.org/platform/) for mor information.

### What is the maximum number of users allowed on the hub?

There is no maximum capacity. 2i2c can deploy hubs in the cloud that can scale resources for as many users as you need. The Catalyst Project funds cover the resource costs.

### What's the maximum storage capacity on the hub?

Again, the same answer as the above applies. We advise extra caution here since storage costs can be expensive. Please consult the [2i2c Service Guide – Data and Filesystem](https://docs.2i2c.org/user/topics/data/) for guidance.

### What kind of hardware is available on the hub?

For Africa we provision hubs using Amazon Web Services (AWS) instances in the `af-south-1` region. For Latin America we provision hubs using Google Cloud Platform (GCP) instances in the `southamerica-east1` region. The following default resource allocations are available:

- Up to 2GB of RAM and 1 CPU
- Up to 6GB of RAM and 2 CPUs
- Up to 24GB of RAM and 3 CPUs.

:::{note}
Need more resources? Please [contact](./contact.md) us and we'll work with you to find a solution that fits your needs.
:::

### Are GPU computing resources available?

This feature is not available on all Catalyst hubs by default. We are happy to enable GPUs for your hub if required – please contact [2i2c support](https://docs.2i2c.org/support/).

### Is shared object storage available?

This feature is not available on all Catalyst hubs by default. We are happy to enable [shared object storage](https://docs.2i2c.org/user/topics/data/object-storage/) for your hub if required – please contact [2i2c support](https://docs.2i2c.org/support/).

### How do I install software on the hub?

We provide two standard community-maintained software images for all Catalyst hubs:

1. [Jupyter SciPy Notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-scipy-notebook)
1. [Rocker Geospatial with RStudio](https://rocker-project.org/images/)

We also provide a third option for you to "Bring your own image" to the hub. [See the 2i2c Service Guide – Customize a community-maintained upstream image](https://docs.2i2c.org/admin/howto/environment/customize-image/) for guidance on how you can add packages to an existing image.
