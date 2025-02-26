# Rails Dynamic Request Lab


## Objectives

* Draw a route with a dynamic variable

* Use a routes variable in params within the logic of an action

* Assign an instance variable in a controller action

* Use a controller instance variable to generate a dynamic ERB template.

* Build a classical show action/view


## Instructions

There are three RSpec/Capybara specs in this lesson; you can find them in `spec/features/student_spec.rb`. Make sure they pass without breaking the other tests. To complete this section, all specs should pass.

In this lab, you will work through the full MVC pattern by building a student management app for The Flatiron School. At a high level, you will integrate the following scenario in your application:

1. The user is able to go to `/students/2` to receive information on the student with an id of `2`

2. The application should render the values from the `student` record in the database


## Keys to remember

* Make sure that you use a route variable for the `show` request path

* If you google around and discover generators/scaffolds, **don't use them** for this lab

## Resources
* [Documentation](http://api.rubyonrails.org/classes/ActionDispatch/Routing.html)

* [Reading](https://github.com/learn-co-curriculum/rails-dynamic-request-readme)

## Does this need an update?

Please open a [GitHub issue](https://github.com/learn-co-curriculum/phrg-rails-dynamic-request-lab/issues) or [pull-request](https://github.com/learn-co-curriculum/phrg-rails-dynamic-request-lab/pulls). Provide a detailed description that explains the issue you have found or the change you are proposing. Then "@" mention your instructor on the issue or pull-request, and send them a link via Connect.

<p data-visibility='hidden'>PHRG Rails Dynamic Request Lab</p>
