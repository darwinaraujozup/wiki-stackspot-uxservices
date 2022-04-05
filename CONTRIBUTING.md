# **Contributing Guide**

This is Stackspot's documentation contributing guide. We'd love to accept your patches and contributions to this project. There are just a few small guidelines you need to follow.

## **Table of contents**
### 1. [**Before you contribute**](#before-you-contribute)
### 2. [**Prerequisites**](#prerequisites)
> #### 2.1. [**Developer Certificate of Origin**](#developer-certificate-of-origin)
> #### 2.2. [**Pull Requests**](#pull-requests) 
> #### 2.3. [**Code Review**](#code-review)   
### 3. [**How to contribute?**](#how-to-contribute?)
 > #### 3.1. [**Issues**](#issues)
> #### 3.2. [**Opening a Pull Request**](#opening-a-pull-request)

## **Before you contribute**

## **Prerequisites**
Check out the requirements before contributing to the documentation's repository:

### **Developer Certificate of Origin - DCO**

 This is a security layer for the project and for the developers. It is mandatory.
 
 Follow one of these two methods to add DCO to your commits:
 

**1. Command line**
 Follow the steps: 
 **Step 1:** Configure your local git environment adding the same name and e-mail configured at your GitHub account. It helps to sign commits manually during reviews and suggestions.

 ```
git config --global user.name “Name”
git config --global user.email “email@domain.com.br”
```
**Step 2:** Add the Signed-off-by line with the `'-s'` flag in the git commit command:

```
$ git commit -s -m "This is my commit message"
```

**2. GitHub website**

You can also manually sign your commits during GitHub reviews and suggestions, follow the steps below: 

**Step 1:** When the commit changes box opens, manually type or paste your signature in the comment box, see the example:

```
Signed-off-by: Name < e-mail address >
```

For this method, your name and e-mail must be the same registered on your GitHub account.

### **Pull Requests**
When you open a Pull Request, follow the requirements below:

1. Add a title with the following pattern: 

#### **[TYPE]: Description**

#### **TYPE**: Add what your Pull Request (PR) refers to:
- **FEATURE:** PR refers to a new activity.
- **FIX:** PR refers to corrections for the next release.

**Example:** **[FIX]: Fix a broken link**

2. Answer the questions about what you did. Add a short description for the changelog, see an example below:

- What did I do? 
Added new items to the Concepts page.

### **Code Review**
- All your submissions need a review from a Technical Writing team member.

## **How to contribute?**
You can suggest a change, a fix, or improvements to our documentation, such as:

- Add a new feature.
- Add missing information.
- Fix a grammar or code error.
- Suggest a new section.
- Translate.

### **Issues**
To open or track an issue for this project, in order to better coordinate your discussions, we recommend that you use the [**Issues tab**](https://github.com/stack-spot/orange-docs-org/issues) in this repository.

- [**GitHub Issues**](https://github.com/stack-spot/orange-docs-org/issues)

### **Opening a Pull Request**

Follow the steps below:

**Step 1.** Clone the documentation repository;

**Step 2.** Create your own branch from the lastest one. 
>Do not create a branch with the release-VERSION name;

**Step 3.** Make your changes. Use the templates to follow a documentation pattern. Check out the [**templates repository**](https://github.com/stack-spot/stackspot-doc-templates).

**Step 4.** Open a pull request to the branch you want your changes in, i. e., **`release-VERSION`** and fill in the template; 


**Step 5.** Stackspot Technical Writing team will check your issue, review it, and then approve your PR.