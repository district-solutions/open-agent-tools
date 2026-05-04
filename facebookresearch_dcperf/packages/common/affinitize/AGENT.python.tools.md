# Agent Python Tools

- repo: facebookresearch/dcperf
- repo_uri: https://github.com/facebookresearch/dcperf

## File: facebookresearch_dcperf/packages/common/affinitize/affinitize_nic.py

Prompts

```
['run the CLI tool to affinitize NIC IRQs to specific CPU cores on a network interface', 'run the CLI tool with --show to display IRQ, RPS, and XPS configuration for a NIC', 'run the CLI tool with --randomize to daemonize and periodically rebalance NIC interrupts across CPUs', 'run the CLI tool with --rps and --xps flags to enable receive and transmit packet steering', 'run the CLI tool with --dry-run to preview IRQ affinity changes without applying them', 'configure IRQ affinity, RPS, and XPS for a network device using provided policy options', "update CPU affinity masks for IRQs of a network device's queues with a scheduling policy", 'configure transmit packet steering based on IRQ affinity for a network device', 'configure receive packet steering for a network device using same-node or all-nodes policy', 'collect IRQ numbers used by a NIC for packet forwarding from proc interrupts or MSI dir']
```

Usage

```
{'run_affinitize_irqs': 'run the CLI tool to affinitize NIC IRQs to specific CPU cores on a network interface', 'run_show_netdev': 'run the CLI tool with --show to display IRQ, RPS, and XPS configuration for a NIC', 'run_randomize_interrupts': 'run the CLI tool with --randomize to daemonize and periodically rebalance NIC interrupts across CPUs', 'run_configure_rps_xps': 'run the CLI tool with --rps and --xps flags to enable receive and transmit packet steering', 'run_dry_run_affinitize': 'run the CLI tool with --dry-run to preview IRQ affinity changes without applying them'}
```

## File: facebookresearch_dcperf/packages/common/affinitize/affinitize_nic_lib.py

Prompts

```
['run the CLI tool to affinitize NIC IRQs to specific CPU cores on a network interface', 'run the CLI tool with --show to display IRQ, RPS, and XPS configuration for a NIC', 'run the CLI tool with --randomize to daemonize and periodically rebalance NIC interrupts across CPUs', 'run the CLI tool with --rps and --xps flags to enable receive and transmit packet steering', 'run the CLI tool with --dry-run to preview IRQ affinity changes without applying them', 'configure IRQ affinity, RPS, and XPS for a network device using provided policy options', "update CPU affinity masks for IRQs of a network device's queues with a scheduling policy", 'configure transmit packet steering based on IRQ affinity for a network device', 'configure receive packet steering for a network device using same-node or all-nodes policy', 'collect IRQ numbers used by a NIC for packet forwarding from proc interrupts or MSI dir']
```

Usage

```
{'configure_netdev': 'configure IRQ affinity, RPS, and XPS for a network device using provided policy options', 'configure_smp_affinity': "update CPU affinity masks for IRQs of a network device's queues with a scheduling policy", 'configure_xps': 'configure transmit packet steering based on IRQ affinity for a network device', 'configure_rps': 'configure receive packet steering for a network device using same-node or all-nodes policy', 'collect_netdev_irqs': 'collect IRQ numbers used by a NIC for packet forwarding from proc interrupts or MSI dir'}
```

