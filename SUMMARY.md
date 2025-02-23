# Table of contents

* [Welcome to BlockScout](README.md)

## About BlockScout <a id="about"></a>

* [Features](about/features.md)
* [Use Cases](about/use-cases/README.md)
  * [Hosted Blockscout](about/use-cases/hosted-blockscout.md)
  * [Self-hosted BlockScout on AWS](about/use-cases/self-hosted-blockscout-on-aws.md)
  * [Self-hosted BlockScout on BYO Servers](about/use-cases/self-hosted-blockscout-on-byo-servers.md)
* [Roadmap](about/roadmap.md)

## For Developers

* [Information & Settings](for-developers/information-and-settings/README.md)
  * [General Requirements / BlockScout Prerequisites](for-developers/information-and-settings/requirements.md)
  * [ENV Variables](for-developers/information-and-settings/env-variables.md)
  * [Deprecated ENV Variables](for-developers/information-and-settings/deprecated-env-variables.md)
  * [Database Storage Requirements](for-developers/information-and-settings/database-storage-requirements.md)
  * [Umbrella Project Organization](for-developers/information-and-settings/untitled.md)
  * [Client Settings \(Parity, OpenEthereum, Hyperledger Besu, Geth, Ganache\)](for-developers/information-and-settings/client-settings-parity-geth-ganache.md)
  * [Deployment Differences Between Chains](for-developers/information-and-settings/deployment-differences-between-chains.md)
  * [Add Validator MetaData](for-developers/information-and-settings/add-validator-metadata.md)
  * [ShareLock](for-developers/information-and-settings/sharelock.md)
  * [haproxy Settings for Blockscout.com](for-developers/information-and-settings/haproxy-settings-for-blockscout.com.md)
  * [Docker Integration \(Local Use Only\)](for-developers/information-and-settings/docker-integration-local-use-only.md)
* [Ansible Deployment \(AWS Cloud\)](for-developers/ansible-deployment/README.md)
  * [Overview](for-developers/ansible-deployment/overview.md)
  * [Prerequisites](for-developers/ansible-deployment/prerequisites.md)
  * [AWS Permissions & Settings](for-developers/ansible-deployment/aws-permissions/README.md)
    * [Creating a Secret Key Pair](for-developers/ansible-deployment/aws-permissions/creating-a-secret-key-pair.md)
    * [Login with AWS CLI](for-developers/ansible-deployment/aws-permissions/login-with-aws-cli.md)
    * [Creating an AWS certificate for SSL](for-developers/ansible-deployment/aws-permissions/creating-an-aws-certificate-for-ssl.md)
    * [Manually Cleaning Terraform Related Instances](for-developers/ansible-deployment/aws-permissions/manually-cleaning-terraform-related-instances.md)
  * [Variables](for-developers/ansible-deployment/variables.md)
  * [Deploying the BlockScout Infrastructure](for-developers/ansible-deployment/deploying-the-blockscout-infrastructure.md)
  * [Deploying BlockScout](for-developers/ansible-deployment/deploying-blockscout.md)
  * [Destroying Provisioned Infrastructure](for-developers/ansible-deployment/destroying-provisioned-infrastructure.md)
  * [Common Additional Tasks](for-developers/ansible-deployment/common-additional-tasks.md)
  * [Common Errors and Questions](for-developers/ansible-deployment/common-errors-and-questions.md)
* [Manual Deployment](for-developers/manual-deployment/README.md)
  * [Manual cleaning an instance from the previous deployment](for-developers/manual-deployment/check-your-manual-deployment-instance.md)
* [Configuration Options](for-developers/configuration-options/README.md)
  * [CSS Configuration & Presets](for-developers/configuration-options/css-configuration-and-presets.md)
  * [Branding Configs](for-developers/configuration-options/branding-configs.md)
  * [Automating Restarts](for-developers/configuration-options/automating-restarts.md)
  * [Front-end Config Files](for-developers/configuration-options/front-end-config-files.md)
  * [Circle CI Updates](for-developers/configuration-options/circle-ci-updates.md)
  * [Internationalization](for-developers/configuration-options/internationalization.md)
  * [Metrics](for-developers/configuration-options/untitled-2.md)
  * [Tracing](for-developers/configuration-options/tracing.md)
  * [Memory Usage](for-developers/configuration-options/memory-usage.md)
* [AWS Marketplace](for-developers/aws-marketplace/README.md)
  * [Overview](for-developers/aws-marketplace/overview.md)
  * [CloudFormation Template](for-developers/aws-marketplace/cloudformation-template.md)
  * [Prerequisites & Install Parameters](for-developers/aws-marketplace/aws-marketplace-installation.md)
  * [Install from AWS Marketplace](for-developers/aws-marketplace/install-from-aws-marketplace.md)
  * [AWS EC2 archive node setup with OpenEthereum \(formerly Parity\)](for-developers/aws-marketplace/aws-ec2-archive-node-setup.md)
  * [Updating & Redeploying in AWS](for-developers/aws-marketplace/updating-and-redeploying-in-aws.md)
  * [Customizing CSS](for-developers/aws-marketplace/customizing-css.md)
* [Testing](for-developers/testing.md)
* [Contributing to BlockScout](for-developers/contributing-to-blockscout.md)
* [Db schema](for-developers/db-schema.md)

## For users

* [Smart Contract Interaction](for-users/smart-contract-interaction/README.md)
  * [Verifying a Smart Contract](for-users/smart-contract-interaction/verifying-a-smart-contract/README.md)
    * [Contract Verification via Sourcify](for-users/smart-contract-interaction/verifying-a-smart-contract/contracts-verification-via-sourcify.md)
  * [EVM Version Information](for-users/smart-contract-interaction/evm-version-information.md)
  * [ABI-Encoded Constructor Arguments](for-users/smart-contract-interaction/abi-encoded-constructor-arguments.md)
* [API](for-users/api/README.md)
  * [GraphQL in Blockscout](for-users/api/graphql.md)
* [FAQs](for-users/faqs/README.md)
  * [How do I speed up my hosted BlockScout instance?](for-users/faqs/how-do-i-speed-up-my-hosted-blockscout-instance.md)
  * [How can I customize the coin symbol?](for-users/faqs/how-can-i-customize-the-coin-symbol.md)
  * [How do I disable exchange rates?](for-users/faqs/how-do-i-disable-exchange-rates.md)
  * [How do I manage deployment with AWS CodeDeploy?](for-users/faqs/how-do-i-manage-deployment-with-aws-codedeploy.md)
  * [How do I replace missing assets/version number in my BlockScout deployment?](for-users/faqs/i-am-missing-assets-version-number-in-my-blockscout-deployment.md)
  * [How do I fix the Gettext.Error?](for-users/faqs/how-do-i-fix-the-gettext.error.md)
  * [How do I fix indexer timeouts?](for-users/faqs/how-do-i-fix-indexer-timeouts.md)
  * [How do I update memory consumption to fix indexer memory errors?](for-users/faqs/how-do-i-update-memory-consumption-to-fix-indexer-memory-errors.md)
  * [How do I update menu links in the header / footer?](for-users/faqs/how-do-i-update-menu-links-in-the-header-footer.md)
  * [What does "In" or "Out" label mean](for-users/faqs/what-does-in-or-out-label-mean.md)

## For projects

* [Premium Features](for-projects/premium-features/README.md)
  * [Custom / Branded Themes](for-projects/premium-features/custom-branded-themes.md)
  * [Hosted Instance on BlockScout.com](for-projects/premium-features/your-chain-on-blockscout.com.md)
  * [Moonbeam Support](for-projects/premium-features/moonbeam-support.md)
  * [Export to CSV](for-projects/premium-features/export-to-csv.md)
  * [Premium Transaction Pages](for-projects/premium-features/premium-transaction-pages.md)
  * [ERC-1155 Support](for-projects/premium-features/erc-1155-support.md)
* [List of Projects Using BlockScout](for-projects/supported-projects.md)

## Resources

* [Media kit](resources/media-kit.md)
* [Discord Channel](https://discord.gg/ZUnrZTK)
* [Forum](https://forum.poa.network/c/blockscout)
* [Gitter Channel](https://gitter.im/poanetwork/blockscout)
* [GitHub Repo](https://github.com/poanetwork/blockscout)

