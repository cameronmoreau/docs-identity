# Single Sign-On (SSO) for PCF Docs

This repo contains the documentation for Single Sign-On for PCF, which enables Pivotal Cloud Foundry users to
authenticate with an external identity provider rather than having to create a new account or re-enter credentials. Single Sign-On grants users centralized access to applications in various spaces, as well as to Ops Manager, Apps Manager, and other Cloud Foundry components.

### Branch Management

| Branch name | Use for… | Publishes to… |
|-------------| ------|--------|
|**master** | This branch is on staging. When 1.6 was released, master and v1.6 were identical. Keep master up to date with any v1.6 fixes. | <a href="https://docs-pcf-staging.cfapps.io/p-identity/1-7/">https://docs-pcf-staging.cfapps.io/p-identity/1-7/</a> |
|**master-pws** | This branch contains PWS-specific SSO content. | <a href="https://docs.run.pivotal.io/sso/index.html">https://docs.run.pivotal.io/sso/</a>| 
|**1.6** | This branch contains the published documentation for the (current) v1.6 release of SSO. | <a href="https://docs.pivotal.io/p-identity/1-6/">https://docs.pivotal.io/p-identity/1-6/</a>|
|**1.5** | This branch contains the published documentation for the v1.5 release of SSO. | <a href="https://docs.pivotal.io/p-identity/1-5/">https://docs.pivotal.io/p-identity/1-5/</a>|
|**1.4** | This branch contains the published documentation for the v1.4 release of SSO. |  <a href="https://docs.pivotal.io/p-identity/1-4/index.html">https://docs.pivotal.io/p-identity/1-4/</a>|
|**1.3** | This branch contains the published documentation for the v1.3 release of SSO. | <a href="https://docs.pivotal.io/p-identity/1-3/index.html">https://docs.pivotal.io/p-identity/1-3/</a>|
|**1.2** | **Do not update**. This branch is obsolete. | <a href="https://docs.pivotal.io/archives/docs-identity-1.2.pdf">https://docs.pivotal.io/archives/docs-identity-1.2.pdf</a>|
|**1.1** | **Do not update**. This branch is obsolete. | <a href="https://docs.pivotal.io/archives/docs-identity-1.1.pdf">https://docs.pivotal.io/archives/docs-identity-1.1.pdf</a>|
|**1.0** | **Do not update**. This branch is unpublished. The branch contains the  documentation for the EOL'd v1.0.10 release of SSO.| _N/A_ |
| **master-on-April27** | A temporary snapshot of master to keep while we make large changes to the master branch. Please keep in sync with v1.6. | _N/A_ |

### Books that Use This Repository

[docs-book-identity](https://github.com/pivotal-cf/docs-book-identity/blob/master/config.yml)

[docs-book-runpivotal](https://github.com/pivotal-cf/docs-book-runpivotal/blob/master/config.yml)
