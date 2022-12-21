# Platform or Security Admin Onboarding

### Pre-requisite
1. locally clone the sandbox landing zone repo
1. create a branch of main

## Add admin folder(s) to the landing zone repository

1. Move into the landing folder
    ```
    cd source-base
    ```
1. get the hierarchy/admin-sandbox package
      ```
      kpt pkg get https://github.com/GoogleCloudPlatform/pubsec-declarative-toolkit.git/solutions/hierarchy/admin-sandbox@main ./landing-zone/hierarchy/Testing/<admin name>
      ```
1. To modify any of the files in this package (like setters.yaml) follow this generic guidance
  
    Refer to the `Make Code Changes` section of the ![Changing.md](Changing.md)

1. Generate hydrated files

    Refer to the `Generate hydrated files` section of the ![Changing.md](Changing.md)

1. Add changes to repository
    
    Refer to the `Add changes to repository` section of the ![Changing.md](Changing.md).