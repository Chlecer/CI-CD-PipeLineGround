# pipelines
Some simple examples using Jenkins pipelines.

[As you know](https://www.jenkins.io/doc/book/pipeline/syntax/) we can have two types of pipelines syntax:
- **Declarative** - relatively recent addition to Jenkins Pipeline (2.5 Version) which presents a more simplified and opinionated syntax on top of the Pipeline sub-systems.
- **Scripted** - unlike Declarative, is effectively a general-purpose DSL built with Groovy (were once the standard).

The two syntaxes are not directly interchangeable, but an answer to a problem for one syntax flavor can usually be converted into the other. The underlying language of both is Groovy, a fully featured programming language independent of Jenkins.

How to know the Groovy version that we are using when running our pipelines?
Just go to to ${YOUR_JENKINS_URL}/about and search for Apache Groovy at **Mavenized dependencies**

Supported links:
[Declarative-vs-scripted-pipelines-Whats-the-difference](https://www.theserverside.com/answer/Declarative-vs-scripted-pipelines-Whats-the-difference)
[Jenkins Administrator's Guide](https://www.packtpub.com/product/jenkins-administrator-s-guide/9781838824327)

To generate some snippets you can use the [official Snippet Generator](https://www.jenkins.io/doc/book/pipeline/getting-started/#snippet-generator) at ${YOUR_JENKINS_URL}/pipeline-syntax.
