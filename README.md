## Automating your Personalize workflow using AWS Step Functions Data Science SDK

As machine learning (ML) becomes a larger part of companies’ core business, there is a greater emphasis on reducing the time from model creation to deployment. In November of 2019, AWS released the AWS Step Functions Data Science SDK for Amazon SageMaker, an open-source SDK that allows developers to create Step Functions-based machine learning workflows in Python. You can now use the SDK to create reusable model deployment workflows with the same tools you use to develop models. You can find the complete notebook for this solution in the “automate_personalize_workflow” folder of our GitHub repo.
This post demonstrates the capabilities of the Data Science SDK with a common use case: how to automate Personalize. In this post, you create a serverless workflow to train a movie recommendation engine. Finally, the shows how to trigger a workflow based off a periodic schedule.


## License

This library is licensed under the MIT-0 License. See the LICENSE file.

