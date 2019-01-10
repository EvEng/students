I am Tanner Hobson and I'm a graduate student with Dr. Jian Huang working on data systems and data visualization.

I'm hoping to get more experience working with graph datasets and doing analyses on them in the realm of visualization.

I'll be working with Jerry Duncan on a GitHub-related project to help developers make better choices about their dependencies.
We'll accomplish this by looking at dependency chains of projects on NPM and matching them to GitHub projects and commits.
This will include ideas from this class like big data (working with the entire set of all GitHub commits), data correctness (determining whether we have correct commits), modeling (combining all resources into single records that we can work with).
In the first phases of the project, we have a couple of main goals:

1. Download the entire dependency graph from NPM using unpkg.org or directly from npmjs.com
2. Process the data so it is sliceable across time (i.e. give the full graph at a specific date).
3. Correlate these versions with GitHub commits and consequently repository states.
4. Provide these results as a web API and build a visualization on top of it.
