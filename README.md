# **Blog Starter Template**

## **Overview**

_The Blog Starter Template includes everything you need to begin building your blog on Yext. This template will jumpstart your next project with a Yext Content configuration, sample data and a statically generated blog site built on Yext Pages._

## **What’s Included**

### Content

#### Entity types & entities

##### Blog

This template includes a custom **Blog** entity type as well as four sample blog posts, each represented as a single Blog entity. This entity type includes fields for key information including body content, author and more.

See the Fields section below for a full list of fields included.

##### Home Page

This template includes a custom **Home Page** entity type as well as one sample Home Page entity. This entity is used to store information that is referenced on the home page of the included blog site. This makes it easy to edit the information displayed on the site directly from within the Yext CMS.

See the Fields section below for a full list of fields included.

##### Site

This template includes a custom **Site** entity type as well as one sample Site entity. This entity is used to store information that is referenced across every template of the included blog site. This makes it easy to edit site-wide information to be displayed on the site directly from within the Yext CMS.

See the Fields section below for a full list of fields included.

#### Fields

##### Blog Fields

The Blog entity type makes use of several built-in fields available within Yext Content including the Name, Slug and Date Posted fields. It also makes use of the following custom fields included with the template:

- Blog Author
- Body
- Description
- Meta Description
- Keywords

##### Home Page Fields

The Home Page entity type makes use of several built-in fields available within Yext Content including the Name, Slug and Business Logo fields. It also makes use of the following custom fields included with the template:

- Cover Photo
- Heading
- Sub Heading
- Featured Blogs

##### Site Fields

The Site entity type makes use the built-in Name and Business Logo fields as well as the following custom fields included with the template:

- Header Links
- Footer Links

### Pages

This template includes a Studio-compatible, statically generated blog built on Yext Pages and powered by the Yext Content configuration described above.

#### Templates

The repo includes two streams templates: one for the home page and one for individual blog pages. These templates are used to statically generate pages for each entity defined in the Content section above. Read more about templates in Pages [here](https://hitchhikers.yext.com/docs/pages/templates/).

### Analytics

This template includes a custom dashboard titled Blog Analytics. This simple dashboard includes insights on total page views over time as well as page views for each individual entity-powered page to monitor engagement with your new blog.

## **Installation Guide**

### Pre-requisites

This template requires access to the following Yext products:

- Content
- Pages
- Analytics

### How to Install

1. In the Yext platform, navigate to **Apps > Solutions**.
2. Select the **Blog Starter Template**.
3. Click **View Solution**. This will open up the Admin Console, an account configuration tool that will allow you to add all of the resources mentioned above to your account.
4. In the upper right corner, click **Apply**.
5. A modal window will open and prompt you to **enter your Account ID**. You can quickly find this in the URL of your Yext account, which takes the form of “[www.yext.com/s/{accountId}/…](http://www.yext.com/s/{accountId}/…)”. Enter the ID and click **Continue**.
6. In the new modal, click **Start authorization flow**. This will open a new window. When prompted, click **Authorize**. Once you receive authorization confirmation, navigate back to the Admin Console window and click **Continue**.
7. Enter your Account ID as the value for the **businessId** variable you are prompted for, then click **Save**.
8. A modal window will pop up showing all of the resources that will be added / edited within your account. Click **Continue** and, when prompted, click **Confirm**.
9. In the Console, you’ll see the message “Applying resources…”. Wait while the resources are applied. You’ll see messages in the console for each resource that is applied and will eventually receive a message saying “Successfully applied resources”.
10. You’re done! All of the template’s resources have been added to your account. Jump back into your Yext account and explore your new resources!
