# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "projectName" : "appsso-starter-java",
  "includeBuildToolWrapper" : true,
  "appssoOfferingName" : "my-login",
  "bsGitRepository" : "github.com?owner=stuartblackburnvmware&repo=appsso-starter-java"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Combo, Combo, Provenance)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [catalog/*.yaml, config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml, config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [catalog/*.yaml, config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [appsso-starter-java->appsso-starter-java]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will replace [
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info   name: appsso-starter-java->
┃ ┃ ┃ ┃ ┃ ┗ ┗  Info   name: appsso-star...(truncated), app.kubernetes.io/part-of: appsso-starter-java->app.kubernetes.io/pa...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [<your-selected-appsso-offering>->my-login]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [gradlew*, gradle/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug gradle/wrapper/gradle-wrapper.properties matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1].validated.delegate (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol repoUrl with value 'https://github.com?owner=stuartblackburnvmware&repo=appsso-starter-java'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1].validated.delegate.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(OpenRewriteRecipe, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1].validated.delegate.in.transformations[0] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1].validated.delegate.in.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace regex '(?<beforeBranch>[\s\S]+)(?<branch>branch: [\S]+)(?<rest>[\S\s]*)' with '${beforeBranch}branc...(truncated)'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[2].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java matched [**] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/application-local.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'settings.gradle', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/authenticated-home.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/home.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/images/tanzu-logomark.svg', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build.gradle', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/styles/main.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzuignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing first 
┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java', will use the one appearing first 
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[2] (Provenance)
┗ ╺ engine.transformations[1] (UniquePath)
```
