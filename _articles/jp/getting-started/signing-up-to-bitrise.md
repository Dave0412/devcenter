---
changelog: 
last_modified_at: 
tag: []
title: Bitriseへのサインアップ
redirect_from:
- "\t https://devcenter.bitrise.io/jp/getting-started/signing-up/signing-up-with-email"
- "/jp/getting-started/signing-up/signing-up-with-email/"
- "/jp/getting-started/signing-up/signing-up-with-gitlab/"
- "/jp/getting-started/signing-up/signing-up-with-bitbucket/"
- "/jp/getting-started/signing-up/signing-up-with-github/"
description: ''
summary: ''
menu:
  getting-started-main:
    weight: 1

---
{% include not_translated_yet.html %}

You can authenticate yourself with your GitHub, Bitbucket or GitLab user against Bitrise. It brings some practical benefits, like logging in with one click and of course you won't have to authorize your Git account when adding repositories hosted by these providers again. You can of course sign up to Bitrise using your email address as well, and log in through your user credentials.

{% include message_box.html type="info" title="Trial after signing up" content="If you sign up for a free account, you will automatically be granted a two-week trial on our Developer plan. This includes:

* 45 minutes of build time.
* 1000 builds a month.
* A maximum of 100 team members.

Read more about the available plans on the [Pricing](https://www.bitrise.io/pricing/teams) page!"%}

## Signing up with a Git provider

1. You can sign up to Bitrise through the **Start for free** button in the upper right corner of [Bitrise](https://www.bitrise.io/ "https://www.bitrise.io/").![](/img/startforfree.png)
2. On the **Sign up** page, scroll down to the **OR SIGN UP WITH** section where you can pick a git provider.![](/img/signuppage.png)

### Authorizing Bitrise with a Git provider

You have to authorize Bitrise before we can establish the connection. This means you give permission to Bitrise to access (read) your repositories.

#### GitHub

![](/img/authorize-github.png)

If you press the **Authorize application** button on GitHub, you will be redirected to Bitrise.

#### Bitbucket

![](/img/authorize-bitbucket.png)

If you press the **Grant access** button on Bitbucket, you will be redirected to Bitrise.

**GitLab**

![](/img/authorize-gitlab.png)

If you press the **Authorize** button on Gitlab, you will be redirected to Bitrise.

### Finishing signup

You will have to pick a username and a password for your Bitrise account. This way you are free from relying on the given service’s availability, and you are also able to connect more accounts. Last, but not least, you don’t have to stick to your connected account’s username.

1. Pick a username and a password for your Bitrise account on the **Sign up** page.

   Please note that you must provide a **strong password** which fulfills these requirements:
   * It should have at least 8 characters.
   * One upper case character.
   * One lower case character.
   * One number.
   * Cannot contain the same character more than 3 times in a row (aaa).
   * Cannot contain your email or username.![](/img/signuppage-1.png)
2. Check your inbox for a confirmation email from Bitrise and follow the instructions ther![](/img/checkyourinbox.png)
3. We can personalize your onboarding experience if you provide which CI/CD tool you have been using so far.![](/img/personalize.png)

After that, you are ready to roll. Add your first app on your Dashboard!![](/img/firstpage.png)

## Signing up with email

You can easily sign up to Bitrise with your email address.

1. Add your email address, username, and password on our [Sign up](https://app.bitrise.io/users/sign_up "https://app.bitrise.io/users/sign_up") page. Make sure you provide a strong password. If it’s been exposed in data breaches, you will get a **Your password is not safe** message with [instructions](https://haveibeenpwned.com/Passwords "https://haveibeenpwned.com/Passwords") on how to provide a secure password.![](/img/signuppage-1.png)
2. Click the **Sign up** button.
3. Check your inbox for our **Confirmation Instructions** and follow the instructions there. If you haven’t received a confirmation email from us, click the **Resend confirmation email** button.![](/img/checkyourinbox.png)
4. We can personalize your onboarding experience if you provide which CI/CD tool you have been using so far.![](/img/personalize.png)
5. Click **Done**. You will be directed to your Bitrise Dashboard. Now you can go ahead and add your first app to your Dashboard.

   ![](/img/firstpage.png)

## Signing up with SSO

You can sign up to Bitrise and join a Bitrise Workspace using the Workspace's [SAML SSO](/team-management/organizations/saml-sso-in-organizations/).

{% include message_box.html type="important" title="Before signing up" content="On the IdP side, the Administrator has to add you as a user to the Bitrise SAML SSO app's organization. To learn which Bitrise Workspace you should join through SAML SSO, the Bitrise Workspace owner can send you an invitation through the [Group menu](/team-management/organizations/members-organizations/#adding-members-to-workspaces) of the respective Bitrise Workspace."%}

Now let's see how to sign up to Bitrise.

1. Go to our [Sign up](https://app.bitrise.io/users/sign_up) page.
2. Click the **SAML** button.

   You are directed to the **Initiate** **Single Sign-On** page.

   ![{{ page.title }}](/img/saml-sso-sign-up.jpg)
3. Provide the **Bitrise Workspace's Name** that you got from the Bitrise Workspace owner and click **Continue with SSO** so that Bitrise can direct you to Workspace's connected SAML SSO provider.
4. Provide your credentials associated with your SAML SSO account.
5. On the **Almost there** page the **Email** field is automatically populated based on your registered email address at your SAML SSO account. You can alter the provided **Username** as you wish.

   ![{{ page.title }}](/img/signup-saml-almost-there-1.jpg)
6. Click **Finish Sign Up**.
7. Check your mailbox and follow the instructions sent by letsconnect@bitrise.io.
8. We can personalize your onboarding experience if you provide which CI/CD tool you have been using so far on the **Personalize your experience** page.

If all went well, you're landed on your Bitrise Dashboard where you can view the Workspace's apps! If you go to your **Account Settings**, you will see the [Workspace]() you've just joined.