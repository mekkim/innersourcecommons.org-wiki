**Title:** ??  

**Statement of Problem:** Deal with the overhead of having shared code in a separate repository that isn't the same as the project-specific one that is tied to production builds.   

**Context:** Shared code is kept in an accessible repository that is different from SCMs used by the products that use the shared code. Integration, testing and builds might be automated with the product SCM but not the shared code repo.  

**Forces:**
When the shared code is in a separate repository, any use of it could result in forking modifications, leading to complications later when the source is changed by the owning organization.
When starting an inner sourcing program, it is possible there are many SCM systems in use; and, frequently, a new SCM is used for the inner sourcing program. Migrating from one SCM to another is not trivial.
Since the using organization has a copy, they might not be aware of changes to the shared code.
It is difficult and expensive for the using organization to change their automated build process to use a foreign repo.  

**Resolution:**  ??  

**Resulting Context:**
Ideally, overhead is minimized or eliminated. Or integrate the shared code repository in the production build.  

**Author:**  

**Status:** Donut  

