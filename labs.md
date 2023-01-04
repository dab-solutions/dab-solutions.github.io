---
layout: page
title: Labs
nav-menu: true
show_tile: true
---

<!-- Main -->
<div id="main" class="alt">

    <!-- One -->
    <section id="one">
        <div class="inner">
            <header class="major">
                <h1>Labs</h1>
            </header>

            <!-- Content -->
            <p>Below you can find a list of projects we have been working on with our partners and clients.</p>
            <div class="row">
                <div class="4u 12u$(small)">
                    <h4>DHIS2 deployments with LXD</h4>
                    <p>To make more robust DHIS2 deployments on LXD infrastructure, we have released <i>dhis2-tools-dab</i>, a successor of <a href="https://github.com/bobjolliffe/dhis2-tools-ng" target=_blank>dhis2-tools-ng</a>.</p>
                    <p>This new tool brings new features such as lxd cluster support, centralized logging and SIEM capabilities.</p>
                    <p>The code can be found <a href="https://github.com/davinerd/dhis2-tools-dab" target=_blank>here</a>.</p>
                </div>
                <div class="4u 12u$(small)">
                    <h4>DHIS2 server security auditor</h4>
                    <p>This <a href="https://docs.chef.io/inspec/" target=_blank>inspec</a> profile verifies compliance of DHIS2 deployments with CIS benchmarks. It can be run locally or remotely to a container in a local LXD host/cluster. It can also run as part of a CD/CI pipeline or automated deployment scripts.</p>
                    <p>Goal is to ensure DHIS2 has been deployed following international security standards.</p>
                    <p>The code can be found <a href="https://github.com/davinerd/dhis2-inspec" target=_blank>on Github</a>.</p>
                </div>
                <div class="4u 12u$(small)">
                    <h4>Linux workstation compliance: alr</h4>
                    <p>To scale management of Linux workstation for compliace purposes, <i>alr</i> is what you need: it's a wrapper for <a href="https://github.com/CISOfy/lynis" target=_blank>lynis</a> and it automatically scans the machine with a predefined or user-supplied profile tailored to the business needs.</p>
                    <p>To actually manage the reports and make it a fully scalable solution, you will need to leverage the custom crafted web user interface: <i>alr webui</i>, which provides easy to access reports across your fleet.</p>
                    <p>The code for alr can be found <a href="https://github.com/dab-solutions/alr" target=_blank>here</a>.<br/>
                    The code for alr webui can be found <a href="https://github.com/dab-solutions/alr_webui" target=_blank>here</a>.</p>
                </div>
            </div>
            <div class="row">
                <div class="4u 12u$(small)">
                    <h4>Infrastructure as Code</h4>
                    <p>IaC is a must paradigm for resilient cloud-native companies. Here is a list of modules to spin secure infrastructure via Terraform:
                        <ul>
                            <li><a href="https://github.com/dab-solutions/tf_hardened_eks" target=_blank>Hardened EKS cluster</a></li>
                            <li><a href="https://github.com/davinerd/tf_hardened_gke" target=_blank>Hardened GKE cluster</a></li>
                            <li><a href="https://github.com/davinerd/tf_gcp_org_policies" target=_blank>GCP Organizational Policies</a></li>
                            <li><a href="https://github.com/davinerd/tf_cloudwatch_ddos_alerting" target=_blank>Cloudwatch DDoS Dashboard & Alerts</a></li>
                        </ul>
                    You can find more by <a href="https://github.com/davinerd?tab=repositories&q=terraform&type=&language=&sort=" target=_blank>looking at the Github repository</a>.
                    </p>
                </div>
            </div>
            <hr class="major" />
        </div>
    </section>
</div>