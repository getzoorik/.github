<p align="center">
  <a href="https://zoorik.com"><img alt="Zoorik. Reduce cloud cost, autonomously." src="brand/zoorik-reveal-tagline-banner-on-navy-960x240.gif" width="100%"></a>
</p>

<p align="center">
  Two products that reduce your cloud bill while your systems keep serving.
  <br>
  <a href="https://zoorik.com"><b>Website</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://zoorik.com/assessment"><b>Free assessment</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://cal.com/zoorik/talk"><b>Book a demo</b></a>
</p>

<br>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><img src="coral.svg" width="26" height="26" alt="">&nbsp;Coral</h3>
      <b>Kubernetes optimization</b><br>
      <sub>Supported on AKS and EKS · Compatible with your native Karpenter, NAP and Autoscaler</sub>
      <ul>
        <li><b>Monitoring</b>: cost tracked always, every action logged</li>
        <li><b>Recommendations</b>: right sizes, spare nodes and the saving</li>
        <li><b>Workload optimization</b>: CPU and memory requests sized to real use</li>
        <li><b>Node optimization</b>: spare nodes drained one at a time; never creates machines</li>
      </ul>
      <a href="https://zoorik.com/coral">Product page</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://zoorik.com/coral/guide">Product guide</a>
    </td>
    <td width="50%" valign="top">
      <h3><img src="amoeba.svg" width="26" height="26" alt="">&nbsp;Amoeba</h3>
      <b>Block storage optimization</b><br>
      <sub>Supported on Windows and Linux</sub>
      <ul>
        <li><b>Monitoring</b>: used and provisioned space on every disk</li>
        <li><b>Savings insights</b>: what each VM costs, and what you save</li>
        <li><b>Block storage optimization</b>: expands and shrinks online, one disk at a time</li>
      </ul>
      <a href="https://zoorik.com/amoeba">Product page</a>&nbsp;&nbsp;·&nbsp;&nbsp;Coming soon: <a href="https://cal.com/zoorik/talk">book a demo for early access</a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top"><b>Reduce cost</b><br><sub>Pay for what your workloads use, not what was provisioned for the peak.</sub></td>
    <td width="50%" valign="top"><b>Safe by design</b><br><sub>Nodes drain one at a time. A disk leaves the pool only when it is empty.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><b>Reliable</b><br><sub>No code changes. Resizes happen while you keep serving.</sub></td>
    <td width="50%" valign="top"><b>Full visibility</b><br><sub>You decide what each product manages, and see every change it makes.</sub></td>
  </tr>
</table>

### Find your own number

One command in your terminal. One PDF report with your estimated saving at list prices. There is no upload and no telemetry, and you send the report yourself.

```bash
npx zoorik assess coral     # Kubernetes: AKS, EKS, or any cluster kubectl can reach
npx zoorik assess amoeba    # block storage: the data disks of your VMs
```

<sub>Read the code first in <a href="https://github.com/getzoorik/assessment">getzoorik/assessment</a>, or follow the steps at <a href="https://zoorik.com/assessment">zoorik.com/assessment</a>.</sub>

<details>
<summary><b>Connect a cluster to Coral with <code>zoorikctl</code></b></summary>
<br>

| Platform | Install |
|---|---|
| macOS | `brew tap getzoorik/tap && brew trust getzoorik/tap && brew install zoorikctl` |
| Windows | `irm https://get.zoorik.com/windows.ps1 \| iex` |
| Linux | `curl -fsSL https://get.zoorik.com/linux \| sh` |

Then run the `zoorikctl cluster connect` command from the Coral console's "Connect cluster" dialog. Its connect token works once and expires after 60 minutes.

</details>

<details>
<summary><b>Public repositories</b></summary>
<br>

| Repository | What it is |
|---|---|
| [assessment](https://github.com/getzoorik/assessment) | The free assessment scripts |
| [zoorikctl](https://github.com/getzoorik/zoorikctl) | The command that connects a Kubernetes cluster to Coral: releases and installers |
| [homebrew-tap](https://github.com/getzoorik/homebrew-tap) | Homebrew tap for zoorikctl |
| [scoop-bucket](https://github.com/getzoorik/scoop-bucket) | Scoop bucket for zoorikctl |
| [terraform-azurerm-zoorik-coral](https://github.com/getzoorik/terraform-azurerm-zoorik-coral) | Terraform module: the Azure permissions the Coral agent needs on an AKS cluster |
| [terraform-aws-zoorik-coral](https://github.com/getzoorik/terraform-aws-zoorik-coral) | Terraform module: the AWS permissions the Coral agent needs on an EKS cluster |
| [kubernetes-scenarios](https://github.com/getzoorik/kubernetes-scenarios) | Ready-made Kubernetes situations for testing cost optimizers on kind |
| [website](https://github.com/getzoorik/website) | The source of zoorik.com |

</details>

<br>

<p align="center">
  <a href="https://zoorik.com">zoorik.com</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="mailto:founders@zoorik.com">founders@zoorik.com</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://www.linkedin.com/company/zoorik">LinkedIn</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://www.youtube.com/@getzoorik">YouTube</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://x.com/getzoorik">X</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://www.reddit.com/r/zoorik">Reddit</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://medium.com/zoorik">Medium</a>
  <br>
  <sub>Zoorik Private Limited · Bengaluru, India · <a href="https://zoorik.com/privacy">Privacy policy</a></sub>
</p>
