# daas-helm
Helm charts for various DPG as part of DaaS initiative


## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add daas https://<oci-sunbird.github.io/daas-helm

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
daas` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> <alias>/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>


## Charts

<div class="table-wrap"><table class="confluenceTable"><colgroup><col/></colgroup><tbody><tr><th scope="col" class="confluenceTh">Chart Name</th></tr><tr><td class="confluenceTd">certificateapi</td></tr><tr><td class="confluenceTd">certificatesign</td></tr><tr><td class="confluenceTd">claim-ms</td></tr><tr><td class="confluenceTd"><p>filestorage</p></td></tr><tr><td class="confluenceTd">identity</td></tr><tr><td class="confluenceTd">keycloak</td></tr><tr><td class="confluenceTd">registry</td></tr></tbody></table></div><p><br/></p>
</div>
