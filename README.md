# <div align="center">**T3A1 - Workbook**</div>

#### Luke Wheldale

</br>
</br>
</br>

## <div align="center">**Q1 - Provide an overview and description of a standard source control process for a large project**</div>

Source control, is a component of software development, particularly for large projects. It is the practice of managing and tracking changes to code. It plays a crucial role in overseeing modifications to the project's source code, documentation, and digital resources. Its main purpose is to facilitate seamless collaboration among multiple team members while upholding the integrity of the codebase and preserving a comprehensive history of changes [1]. Source code allows you to create a copy of a repository which you can then use to work on code independently from the stable version of the codebase [1].
Below is a description of the process of using source control for a large project.

1. **Version Control System selection:**
   Firstly, one must choose a suitable version control system to use for their project.
   Options include Git, Mercurial, and CVS, among many others.
   The preferred option for most modern projects is Git.
   This is due to Git's widespread adoption, fast performance, cross-platform functionality and robust nature [2].

2. **Repository Setup:** Next, a respository must be created. A repository is a centralised digital storage for users to create and manage changes to a project's source code. The repository stores assets and the project's source code.
   The repository is often hosted on platforms such as GitHub, Bitbucket, GitLab or may be self-hosted [3].

3. **Branching Strategy:** A branching strategy is a method utilised by software development teams when they create, combine, and introduce code while using a version control system. Essentially, it consists of a set of guidelines that developers adhere to, defining their interactions with a shared code repository [4].
   To effectively stick to a project's requirements, a suitable branching strategy must be chosen. The strategy should include the following elements:

-   A main branch, storing code that is production-ready.
-   Feature branches, dedicated to implementing new features or modifications.
-   Release branches, designated for the preparation and stabilisation of upcoming releases.\*
-   Specialized branches for quickly addressing critical production issues via hotfixes [4].

5. **Code Review:**
   When it comes to large projects. Code reviews are important.
   Code reviews typically take place before code is merged to the main branch.
   The review involves approving or declining code, depending if it adheres to code quality and standards.

6. **Continuous Integration:** Continuous integration (CI) is a fundamental practice in software development. It involves developers frequently integrating their code changes into a central repository. Following this integration, automated processes like builds and tests are triggered. CI primarily focuses on the build and integration phases of the software release process. It involves both an automation aspect, which includes tools like CI or build services, and a cultural aspect, which emphasises the importance of regular integration [5].
   The primary goal of CI is to swiftly detect and resolve bugs, enhance the overall quality of software, and shorten the duration required for validating and launching new software updates [5].

</br>

## <div align="center">**Q2 - What are the most important aspects of quality software?**</div>

</br>

<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>

# <div align="center">**References**</div>

[1] [https://aws.amazon.com/devops/source-control](https://aws.amazon.com/devops/source-control/)

[2] [https://www.softwaretestinghelp.com/version-control-software/](https://www.softwaretestinghelp.com/version-control-software/)

[3] [https://aws.amazon.com/what-is/repo/](https://aws.amazon.com/what-is/repo/#:~:text=A%20repository%2C%20or%20repo%2C%20is,of%20documents%20when%20developing%20software.)

[4] [https://www.abtasty.com/blog/git-branching-strategies/](https://www.abtasty.com/blog/git-branching-strategies/#:~:text=A%20branching%20strategy%2C%20therefore%2C%20is,interact%20with%20a%20shared%20codebase.)

[5] [https://aws.amazon.com/devops/continuous-integration/](https://aws.amazon.com/devops/continuous-integration/#:~:text=Continuous%20integration%20refers%20to%20the,for%20a%20release%20to%20production.)
