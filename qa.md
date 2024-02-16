I spoke with an experience QA engineer/manager about their process. Here are the notes I captured.

On outsourcing QA:
- Outsourced QA folks are good at “manual automated” testing. This can be a good option when there are rote tests that are difficult to automate.
- Outsourced QA can also work well when the correct product behavior is obvious, such as a checkout flow.

What’s in your toolbox as a QA engineer or manager?
1. Use the thing. Start out with a lot of hands-on exploration of the product.
1. Observe both the quality of the product and how the team works. Participate in retrospectives and interview team members. Look for process improvements that will help.
   1. For example, you may find there are lots of bugs on Android, and you learn from an engineer that "we never test on Android". Well, then starting testing on Android.
1. Teach the engineers to test. They may not know how to do it very well. Help create a checklist they can run through.
1. Look for potential issues with the process for bug identification and how communication is handled between the support team and the product teams. Look at customer feedback and how observability tools are used to spot issues.
1. Work on building test automation
1. Take a “shift left” approach. For example, read the product spec before anyone starts building. Look for the potential things that could go wrong or get missed. Talk with the engineer to see if they are thinking about those things as well.

What did you see in your QA role that might surprise people?
- Typically, before code goes into production many of the issues are already known. However, the impact of those issues isn’t understood, leading to surprising quality problems. There tends to be an underemphasis on appreciating the impact of an issue.
- The engineering team usually has a good intuitive sense of quality
- Always consider the relative cost of different ways of addressing quality, and focus on what matters

Book recommendation: [Lessons Learned in Software Testing](https://www.amazon.com/Lessons-Learned-Software-Testing-Context-Driven/dp/0471081124)
