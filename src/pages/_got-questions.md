<!-- markdownlint-disable-next-line MD041 -->
You have questions? That's okay! We're here to help, here are the answers to some common questions about CIPP below and answers to more technical or specific questions in the [FAQ](/faq/).

<details><summary>Who are the developers?</summary>

We mostly work for Managed Service Providers (MSPs) who develop CIPP on a voluntary basis though some contributors may receive payment to work on specific features or projects. CIPP development is lead by:

* [Kelvin Tegelaar](https://www.cyberdrain.com)
* [Gavin Stone](https://www.gavsto.com)

Check the [contributors page](/contributors) for details on other contributors.

</details>

<details><summary>How much does it cost?</summary>

CIPP is free, open-source software and is available under the [AGPLv3 license](/docs/dev/licensing/code). Hosting CIPP requires Azure Static Web Apps and Azure Functions at your own cost. Hosting on your own servers or using anything other than Azure isn't supported.

You can, if you wish, donate to support CIPP [on GitHub](https://github.com/sponsors/KelvinTegelaar/), sponsors at certain levels can have CIPP hosted for them by Kelvin.

</details>

<details><summary>Is this secure?</summary>

We built CIPP from the ground up with security in mind. It's built with [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview) and [Azure Static Web Apps](https://docs.microsoft.com/en-us/azure/static-web-apps/overview) and relies on the security provided by Azure Static Web Apps to handle authorization and authentication.

CIPP uses several automated code scanning tools to check for vulnerabilities and make sure that the code is as safe and secure as possible. You are free to audit the code (which you can find in the GitHub repositories linked in the NavBar) and report any issues you find.

Paid code security audits may be undertaken as allowed by funding. If you think you've found a security issue please see the [security policy](/security) for information on how to report these.

</details>

<details><summary>How's CIPP funded?</summary>

Funding for CIPP comes primarily from the sponsors. CIPP also relies on time and effort from [contributors](/contributors).

</details>