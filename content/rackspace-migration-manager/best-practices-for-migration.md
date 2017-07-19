---
permalink: best-practices-for-migration/
audit_date: '2018-06-15'
title: Best practices for migration
type: product
created_date: '2017-06-12'
created_by: Catherine Richardson
last_modified_date: '2017-07-05'
last_modified_by: Catherine Richardson
product: Rackspace Migration Manager
product_url: rackspace-migration-manager
noindex: true
---

As Rackspace Professional Services has worked on migration projects for our
customers, they have discovered some best practices for migrating between cloud
platforms quickly and effectively. This article provides a list of some of
those best practices.

The Rackspace Migration Manager uses the "re-host" method for migration. This
method moves an application to AWS by making little or no changes to its
architecture and configuration. Re-hosting is sometimes called “lift and
shift”. This method is well suited for applications with well-defined
architectures, where components and data are strongly coupled between each
other. This method allows enterprises to take in-house and highly-customized
applications and replicate them in the AWS cloud without modifying their
design.

Other migration approaches are available by engaging with Rackspace
Professional Services.


###Phase 1: Before the migration###

1. Share why the migration is important to the organization.
   To do so, you must have a clear understanding of how the migration will
   affect your organization's strategy.

2. Decide on a cloud governance model, which is a view of IT governance
   focused on accountability, defining decision rights and balancing benefit
   or value, risk, and resources in an environment embracing cloud computing.

3. Identify your organization’s information security needs. Use the right
   controls for the needed security.

4. Train the staff early for a smoother transition and so they can help answer
   questions early on.

5. Determine how operations will take place in AWS. Doing so early helps your
   big-picture thinking so you can ensure your environments align with the
   business strategy.

6. Determine what your current IT assets are and if you are going to include
   them in the migration. Determine what discovery tools to use. Doing this
   helps the migration planning efforts and minimizes the possibility of
   missing a dependency during the migration.

7. Select the right partner to help you with the migration. Look
   for those that have the technical expertise and experience
   migrating to AWS.


###Phase 2: Migration###

1. Start small and simple. For example, you might migrate small workloads
   first, migrate one server at a time, or migrate the pieces that will
   benefit most from the new environment first. The more your staff becomes
   comfortable with AWS services, the easier it will be to gain acceptance
   internally. This requires consistency and transparency.

2. Provide as much automation as possible. Determine what can be automated and
   give your team the power to make it so.

3. Adjust internal processes to embrace this change.

4. Use fully managed services wherever possible.


###Phase 3: After the migration###

1. Have a monitoring strategy in place that monitors your most important
   items. Monitoring data will enable you to make good decisions
   about performance and costs.

2. Use the monitoring tools that best fit the business. Your operations people
   will thank you in the long run and your business owners will have clearer
   data points to base their decisions on.

3. Leverage Rackspace support. The Rackspace Technical Account Managers are
   invaluable resources. They get to be part of your broader virtual cloud team
   and can provide a source of technical information and guidance.


###For mass migrations (migrating many applications at one time)###

1. Have teams, tools, and processes that are centered around the migration
   activities.

2. Provide leadership and set benchmarks for the migration.

3. Provide onboarding for new team members when the project is in full swing.

4. Consider many different criteria when deciding on the migration strategy
   for a particular application -- business objectives, the roadmap,
   risk, costs, and so on. You will either make a decision to move the
   application as-is or modify it in some fashion.

5. Try to use best practices for resiliency and cost savings, and abstract the
   underlying infrastructure when you can. Some common options are
   auto-scaling, load-balancing, multi-AZ scenarios, and right-sizing EC2
   instances.

6. Find patterns and create blueprints for them. Migration patterns will
   emerge based on the strategy chosen. Create re-usable blueprints for
   those patterns. Share them with the migration teams.

7. Test your applications. Each application component should go through
   predetermined, well-documented tests. Sign-off from the business owners
   will be a lot smoother if you ask the application owners to provide you
   with the test plans early on in the project. A template that is used by all
   application owners would be best. Update the template with their specific
   testing requirements.

8. Be sure that there is great communication with all the teams involved.
   Document all migration decisions and make sure everyone agrees with them.
   Be sure that the teams across the organization, including those not directly
   involved in the migration, are aware of any down time, changes of IP
   addresses, or URLs. Also, let any third parties that might have access to
   your systems know what is going on.
