
# Welcome to the Freedonia Institute of Standards and Technology

For background, see: https://github.com/pburkholder/freedonia-compliance and https://github.com/pburkholder/ato1day

To import these data into a OpenControl project add the follow code to your opencontrol.yaml file and use [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project) greater than 1.1.1

```yaml
dependencies:
  standards:
    - url: https://github.com/pburkholder/freedonia-frist/
      revision: master
  certifications:
    - url: https://github.com/pburkholder/freedonia-frist/
      revision: master
```

