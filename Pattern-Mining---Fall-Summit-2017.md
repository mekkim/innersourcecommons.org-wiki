## Pattern Mining from Fall Summit 2017
* Proven solutions with known problems
    - Metrics: You are what you measure - Everyone is required to come up with KPIs to prove something is working; but if you measure the wrong thing, you can reinforce the wrong behaviors. E.g., choose lines of code, you're signaling to the community that you can game the metric by being more verbose. If you can convince management there is another metric close to what you want to incent... Some companies use this to increase collaboration or to incentivize innovation (different measures). 
    - Nearsighted decision making - rolling a one-of vs. reuse. Remind them of the work they're taking on; for active InnerSource domains funding, engineers dedicated via pairing with the engineering resources put into it. Educates them about the long term costs.
    - new patterns for EOL of a project; sometimes projects just need to go bye-bye. One of the main problems is fear. Addressing problems by helping teams contribute in a InnerSource fashion to the newer version (via mentoring) has been helpful and quantifiable (can say how much projects were costing and how much we're saving by reuse and collaboration).
    - Success disease! Need to slow adoption or deal with brand dilution

* Key challenges without solutions (-> express as a donut)
    - not invented here
    - Competing Ideas: kickstarting an InnerSource program; multiple teams coming to solve the same problem. How to mediate the same problem.
    - How to incentivize other teams to contribute into the repository
        - Find an extrinsic reward: We buy donuts for whoever submits a PR; works wonders. Cheap! Can send donuts internationally.
        - Teams are a group of individuals.
        - The bigger problem of cultural transformations. Hearts and minds: getting people to change the way they are doing things isn't an easy answer.
    - Charter mission base teams to contribute to the process; another team with a similar set of goals chartered a team from us but won't go through our process (only getting done what they need to get done)
    - Ownership problem: too much ownership. Quite a few teams that might be the right place for a thing to be owned don't want to own it. We've made it okay (bring the code off of github and deploy) == calling it InnerSouce. But if it is a real-time running thing used by a bunch of teams, but not owned by anyone--who do you call (24x7 SLA)? Management wants to enforce ownership as long as the thing that was built makes sense to be owned.
    - Who supports InnerSource? Companies might establish commercial relationships wtih open source for support. But who supports InnerSource?
    - How do you characterize the benefits (to convince people to get onboard)? Staffing availability, financial terms, etc.
    - Cost of Contributing: Bottom line financial for contributing org: how do you make sure that contributing doesn't become a drag on your financial or productivity by providing support, fixes that you're on the hook for because you contributed.
        - You can set up a financial model with Product Management; if someone wants 24x7 SLA you can get it if you pay for it. We have a team that will be then there to do that. Don't assume (same as with open source)--it's not a black box. If you want to change that assumption, the bill goes up. This covers the cost of contribution through the financial model.
        - In Open Source, the expectation of support isn't there (with community open source). With InnerSource, since your company owns the code, there may be greater expectation that support will be provided.
        - Less understanding of the gift of code. In open source, getting "free" code is a good thing. With most corporations, there is ownership culture (have to deal with this anyway to get collaboration).
    - We open sourced something for a team; the team asked us to support it (without paying). Because you're in the org, there is the big cheese effect (other team can go to your big cheese to ask you to do something).
    - Building software for a business partner; they determine you can either contribute or not (sharing the code with someone else may cause their speed to be slower because they're supporting another team that picks up that code).
    - Send me a pull request (universal FU). We're available for InnerSource.
    - How you manage evolution and possible retirement of component assets you use; the problem you solve 3, 5, 7 years down the road. How do you collaboratively take the contributors and users through the evolution process?
    - We don't talk much about the verification costs. You only have to verify it once when contributing code vs. when you roll your own. Highlighting these measures will show that rolling your own is more expensive than contributing to a common code (contribute fractional amount to testing). 
         - desire to put your patches upstream (motivation: reputation + work that would have to otherwise be done by back patching). In Open Source, permissive licensing didn't require you to contribute changes. Apache said they would rather have a gift of code. We should measure this to reflect we're incurring costs.
         - Being compelled vs. voluntarily giving a gift: having a mandate on high is helpful; but it can be feedback on the InnerSource project--am I contributing and communicating value? Clearly communicating this can help want to opt-in into contributing. IF they don't want to, this is feedback for improving the project.
    - when you contribute upstream, it can help your reputation and you are also pushing your problem upstream, helping to maintain the project. It should be maintained in the upstream project. This should be an encouragement to help people opt in, to make it a magnet to draw contributions.
    - Lifecycle hand-off; if someone leaves the team, how do you hand off the project they are maintaining?
    - How to involve other stakeholders beyond programmers? Who else owns a UI component?
    - InnerSource has open, documented communication, helping new teams get up to speed more quickly.

* Comment: A lot of this is the dichotomy of developers wanting to do the right thing vs. management trying to say how do we control and put some order around this thing. You can either do things from the ground up or the top down. Ground up you can do things to a certain level; then you need executive support. A top down approach can work.
* Taxonomy: being careful with language is important. People who work with open source talk about source code; enterprise people talk about components (and people then think about what they get from a common component on enterprise)--SLA, support. Maybe talk about code and you'll get people thinking a certain way.
* How do we InnerSource patterns for planning? Unified Product Model: support, SLAs for components: creating patterns for each product we're committing to (with different support models). This can also address findability (creating standards, knowing where to go for information).
* How to structure the pattern to force continual review of every pattern? To have a structured limit, a freshness date? Good to have it part of the structure, to force it to come up. Determine the lifecycle. Putting a freshness date will let you know if the pattern is used during that period. Continual review chain. Note the last review date. "Check that this is still true"
* If these turn into patterns, we should ideally put some author attribution (if you want that).
* Jim Coplien: Bread on the water: an idea percolating inside isn't worth anything; but if it goes out and then comes back in, people take it more seriously.
