# docs-cloud-cache

## About Product Name

The name of the product is Pivotal Cloud Cache. 
The name can be abbreviated after first use in body text on the page.
For example: first use in body text is "Pivotal Cloud Cache (PCC)". 
In titles and headings and in subsequent use on the page, use "PCC".

## Branches in this Content Repo 

**master** - use for unreleased documentation

The master branch is the tree-trunk, so ALWAYS make changes you want carried forward in this branch. This includes:

* Unreleased features
* Doc bug fixes
* Doc reorganization or enhancement

Then, if necessary, immediately cherry-pick/copy any changes that you want to push immediately to production into the other "live" branches.

## Partials

Cross-product partials for **Pivotal Cloud Cache** are single sourced from the [PCF Docs Partials](https://github.com/pivotal-cf/docs-partials) repo.

Previously, these partials were sourced from the v018.x branch of the [On Demand Service Broker SDK](https://github.com/pivotal-cf/docs-on-demand-service-broker/tree/v0.18.x) content repo.

## Developing docs locally

This will make the book available at localhost:4567 and automatically update when you write changes to disk

```
cd docs-book-cloud-cache
bundle install
bundle exec bookbinder watch

```
