Here is the **Software Development Checklist**. The purpose of the list is to create a minimum set of tools and rules that are applicable to each quality software project, from one-man army open-source to enterprise giant.

Got the ideas? Create pull request!

# 👩‍💻 Code

* [ ] Conduct **code reviews**.  
    * Use online tool for code reviews.  
* [ ] Develop in pairs (***pair programming***).
* [ ] Use **distributed version control** (preferable **[Git](https://github.com/git/git)**).
    * Do not use zipped files, SVN, TFS, etc.
* [ ] Pull changes (*pull request*), do not push.
    * Use policies for **pull requests** (e.g. build succesful, automated tests passing, changes reviewed).
* [ ] **Monitor and log** your application.
* [ ] Setup separate environments for **development**, **testing** and **production**.
    * Consider **staging** environment.
* [ ] Setup **Continuous Integration (CI) server**.
* [ ] Use **[Semantic Versioning](https://semver.org/)**.

# 📈 Process

* [ ] Use **project management tracking system** (also known as *bug tracker* or *issue tracker*).
    * Automatically hook commit ID with an issue ID.
* [ ] Create two backlogs: **product backlog** and **sprint backlog**.
* [ ] Use **Definition of Done**.
    * ...And **Definition of Ready**.
* [ ] Use **acceptance criteria** (also known as *exit criteria*) to describe stories. Use these to resolve all ambiguations.
* [ ] Use **template for bug ticket** (environment, version or commit ID, reproduction steps, expected behavior).
* [ ] Improve the process by making **small iterative changes** in your process (*kaizen*).

# 📃 Documentation

* [ ] Setup **wiki**-engined documentation.
    * Encourage others to maintain wiki.
* [ ] Create a **big picture diagram** of the project.
* [ ] Create simple **diagrams for the most important flows** of the project.
* [ ] Create a single page with the **list of links** in your organisation.
* [ ] Document on-boarding process — required tools, resources, hacks, etc.
* [ ] Set-up licensing and make it available public.

# 📆 Meetings

* [ ] Always send meeting information via **calendar software**.
    * Include online **conference details** in event details (phone number and/or link).
    *  Always **write agenda**.
    * Consider writing expected outcome.
* [ ] Mark attendees as either **required or non-required**.

# 💬 Team

* [ ]  Use effective **communication tool** (e.g. [Slack](https://slack.com/)) across organisation.
* [ ] Avoid **single point of failure** (with [`Bus.Factor == 1`](https://en.wikipedia.org/wiki/Bus_factor)).
