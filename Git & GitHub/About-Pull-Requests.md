# Pull Request-ების შესახებ
### Pull Request-ები არის ერთგვარი საშუალება "შეტყობინების გაგზავნის" სხვა თანაგუნდელისთვის, რომ თქვენ დაფუშეთ თქვენი ბრენჩი GitHub რეპოზიტორიში. მას შემდგომ, რაც გაიხსნება pull request-ი, თქვენ შესაძლებლობა გაქვთ გამართოთ დისკუსია და განიხილოთ პოტენციური ცვლილებები სხვა თანაგუნდელებთან ერთად, მოახდინოთ დამატებითი ცვლილებები საჭიროებისამებრ და შემდგომ მოახდინოთ საბოლოო "ვერსიის" შერწყმა(merge) მთავარ ბრენჩზე. (master/main)


pull request-ის ინიციალიზების შემდგომ, თქვენ დაინახავთ გადათვალიერების გვერდს (review page), რომელშიც ასახული იქნება თქვენი, ანუ შესადარებელი ბრენჩი და რეპოზიტორიის საბაზისო ბრენჩი(master/main). ზემოხსენებულ გვერდში თქვენ გაქვთ შესაძლებლობა გადახედოთ ცვლილებებს, რომლებიც თავმოყრილია კომიტებში, დაამატოთ ლეიბლები, ვადები და უფლებამოსილი პირი/ები(assignees). ასევე, მოიხსენიოთ(mention) სხვა თანაგუდნელები, ან კონტრიბუტორები. დამატებითი ინფორმაციისათვის ეწვიეთ: [Pull Request-ის შექმნა](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

pull request-ის შექმნის შემდგომ, თქვენ გაქვთ შესაძლებლობა დაფუშოთ კომიტები თქვენი ლოკალური ბრენჩიდან არსებულ pull request-ში. კომიტები გამოჩნდება ქრონოლოგიურად და ცვლილებების ნახვა შესაძლებელია "Files Changed" ტაბში.

სხვა კონტრიბუტორებს შეუძლიათ გადახედონ თქვენ მიერ შეთავაზებულ ცვლილებებს, დაამატონ კომენტარები და კონტრიბუცია შეიტანონ თქვენს pull request-ში.

თქვენ შეგიძლიათ ბრენჩის მიმდინარე deployment სტატუსი და წინარე deployment აქტივობები "Conversation" ტაბში. დამატებითი ინფორმაციისათვის ეწვიეთ: "[Viewing deployment activity for a repository.](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/viewing-deployment-activity-for-your-repository)"

მას შემდგომ, რაც დარწმუნდებით, რომ თქვენ მიერ შეთავაზებული ცვლილებები დადასტურებულია გეძლევათ შესაძლებლობა, რომ შერწყათ/დამერჯოთ pull request-ი.
თუ მუშაობთ `shared repository model`-ში, მაშინ თქვენ ქმნით pull request-ს და თავადვე, ან სხვა შერწყამს თქვენს ცვლილებებს თქვენივე ბრენჩიდან იმ საბაზისო ბრენჩში, რომელსაც თქვენ მიუთითებთ pull request-ში. (ძირითად შემთხვევებში ეს არის master/main ბრენჩი.) დამატებითი ინფორმაციისათვის ეწვიეთ: "[Merging a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/merging-a-pull-request)."

თუ სტატუს ჩექები მოთხოვნილია რეპოზიტორიაში, მაშინ მოთხოვნილმა სტატუს ჩექებმა უნდა გაიაროს წარმატებით იმისათვის, რომ მოხდეს თქვენი ბრენჩის შერწყმა დაცულ ბრენჩზე. დამატებითი ინფორმაციისათვის ეწვიეთ: "[About required status checks](https://docs.github.com/en/free-pro-team@latest/articles/about-required-status-checks)."

თქვენ შეგიძლიათ მიაბათ pull request-ი არსებულ იშუს(Issue), რათა მოხდეს იმ ადამიანების ინფორმირება, რომლებიც ამ საკითხს "კურირებენ". რა იგულისხმება ამაში?
იგულისხმება ის, რომ მათ შეუძლიათ ნახონ, თუ რა სტადიაზეა საკითხი, ხოლო საკითხთან დაკავშირებული ბრენჩის შერწყმის შემდგომ ხდება ავტომატურად დახურვა ამ საკითხის. დამატებითი ინფორმაციისათვის ეწვიეთ: "[Linking a pull request to an issue](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)."

```
Tips: should be added
```

# შაბლონად შენახვა Pull Request-ების

Pull request-ების შაბლონად შენახვა საჯარო რეპოზიტორიებში

როდესაც ქმნით pull request-ს, შეგიძლიათ, რომ შექმნათ ისეთი pull request-ი, რომელიც უკვე მზად არის განსახილველად, ან შეინახოთ შაბლონად. შაბლონური pull request-ებს ვერ დამერჯავთ. დეტალური ინფორმაციისათვის ეწვიეთ: "[Creating a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)" და "[Creating a pull request from a fork](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)."

როდესაც დარწმუნდებით, რომ თქვენი pull request-ი არის სრულყოფილი და მზად არის განსახილველად, მაშინ შეგიძლიათ შაბლონური pull request მონიშნოთ, როგორც განსახილველად მზად მყოფი. ასევე ნებისმიერ დროს შესაძლებელია მიმდინარე pull request-ის შაბლონად შენახვა. დამატებითი ინფორმაციისათვის ეწვიეთ: "[Changing the stage of a pull request.](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/changing-the-stage-of-a-pull-request)."


# დამატებითი საკითხავი

*[Pull request](https://docs.github.com/en/free-pro-team@latest/articles/github-glossary/#pull-request)
*[About branches](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-branches)
*[Commenting on a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request)
*[Merging a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/merging-a-pull-request)
*[Closing a pull request](https://docs.github.com/en/free-pro-team@latest/articles/closing-a-pull-request)
*[Deleting unused branches](https://docs.github.com/en/free-pro-team@latest/articles/deleting-unused-branches)
*[About pull request merges](https://docs.github.com/en/free-pro-team@latest/articles/about-pull-request-merges)