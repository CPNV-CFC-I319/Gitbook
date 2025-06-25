# Behavior Driven Development

Source :&#x20;

[GeeksForGeeks - BDD](https://www.geeksforgeeks.org/behavioral-driven-development-bdd-in-software-engineering/)

[GeeksForGeeks - TDD ](https://www.geeksforgeeks.org/test-driven-development-tdd/?ref=lbp)

## Qu'est-ce que le BDD ?

"Behavior-Driven Development (BDD) testing is a software development approach that <mark style="color:orange;">focuses on the behavior of the system from the end user’s perspective</mark>. It emphasizes collaboration among stakeholders, including developers, QA engineers, and business analysts, to ensure <mark style="color:orange;">that the software meets both business requirements and user expectations</mark>.

In BDD testing, scenarios are described using a domain-specific language (DSL) such as Gherkin, which is easily understandable by both technical and non-technical team members."

## TDD vs BDD

**"Test Driven Development (TDD)** is a software development methodology <mark style="color:orange;">that emphasizes writing</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**tests before writing the actual code**</mark>. It ensures that code is always tested and functional, reducing bugs and improving code quality.&#x20;

In TDD, developers:

* write **small, focused tests** that define the desired functionality,&#x20;
* then write the minimum code necessary to pass these tests, and finally,&#x20;
* refactor the code to improve structure and performance.

This **cyclic process** helps in creating reliable, maintainable, and efficient software. By following TDD, teams can enhance **code reliability**, accelerate **development cycles**, and <mark style="color:orange;">maintain high standards of</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**software quality**</mark>**."**

## Un schéma à garder en tête

1. **Describe behavior –**&#x54;his includes the flow and features of the product, which means the main vision.
2. **Define requirements –**&#x4D;odeled requirements with business rules for a shared understanding.
3. **Run and fail the tests –**&#x44;evelop and run the test cases.
4. **Apply code update –**&#x52;efactor it according to the requirement.
5. **Run and pass the tests –**&#x52;un the updated code and pass the test cases.

{% embed url="https://media.geeksforgeeks.org/wp-content/uploads/20240613150124/Behavior-Driven-Development-bDD-Life-Cycle.webp" %}

## Et Python dans tout cela ?

Voici la configuration qui vous sera demandée d'utilisée pour expérimenter le BDD.

Note : dans cet exemple, on est plus proche du TDD que du BDD.... mais allons-y étape par étape.&#x20;

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Exemple d'implémentation d'un test (TDD) au sein de Pycharm</p></figcaption></figure>
