# Redi's Raw Data Repo // Processing

Welcome to a sub page of the repository. This page is all about `Processing` status.


# What is Processing?

This package may be processing from the finished product or processing through the testing phase. This is the critical section of the package to make sure it is usable and friendly to other DBM Users.

## How does it get processed?

The RD will get tested in many different ways. These include;
- Local Data conflictions,
- Proper usage of command terms,
- Functionality,
- Command User's proper authorisation (permission nodes or special DB/Roles.),
- Command flow of all pathways.

### Local Data Conflictions:

I make sure that all packages are unique and won't interact with other possible conflicting Raw Data or personal commands. I establish this by using a special prefix for every package. It follows as this:

`redipanda.events.data`

redipanda - It's reffering to my RD data;
events - Refers to the Events Module/Package;
data - Refers to the contents of that package.

This can be edited if your using a economy system for example:

`redipanda.economy.balance`
Can be renamed to
`balance`
Which can be interacted with your own local commands.

### Proper usage of command terms:

We want to make sure that all users who have access to the commands included in the packages know where to go if there is a incorrect syntax. In order to go around this challenge, every action which requires multiple parameters will check if the paramters entered fits the correct protocols. If not, a gentle and sweet reminder of using the correct method will be broadcasted.


### Functionality:

Does it work? Does the package perform the tasks required to become that package? Full testing and suggestions are required in order to fufil this task. I make sure that during the publishment process, any feedback in regards to its proper functionality will be taken into account.

### Command User's proper authorisation (permission nodes or special DB/Roles.):

Are these commands suitable for public use or should it be restricted to certain members? My colleagues and I have brainstormed if some commands should be restricted and undergoes testing in a separate environment.

### Command flow of all pathways:

Is there a broken pathway that may break the commands or the logics behind it? I make sure that all pathways are blocked and if upon stubling a pathway that hasn't been set, an error catcher will be ready to catch the error.


