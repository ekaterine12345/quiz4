# quiz4
  მოცემული პროგრამა წარმოადგენს Web Scraping/Parsing მაგალითს. აღნიშნულ პროგრამაში ინფორმაცია მომაქვს codeforces-იდან, შესაბალისად
თითოეული ამოცანისთვის: კოდური სახელი, სათაური, ამ ამოცანის ქულითი შეფასება (რაც რთულადაა მიჩნეული მეტი ქულა აქვს მინიჭებული)
და იმ ადამიანების რაოდენობა, რომლებმაც ეს ამოცანა წარმატებით ამოხსნეს (გაატარეს Accepted). 

  ინფორმაცია მომახვს codeforces-ის bugabooset -> problems-იდან, სადაც არის ამოცანების ლისტინგი. ვიყენებ paging-ს და ინფორმაცია მომაქ
ხუთი გვერდიდან. ვიყენებ რიქვესთებს შორის ლოგიკური ხანგრძლივობას 2-დან 5-წამამდე. ჩემ მიერ მოპოვებილ ინფორმაციას ვწერ csv-ფაილში.

გამოყენებული მაქვს შემდეგი მოდულები: requests, bs4-ის BeautifulSoup, time-ის sleep
random-ის randint

# codeforces
  Codeforces არის ერთ – ერთი საუკეთესო პლატფორმა კონკურენტული კოდირებისთვის და როგორც წესი, ცნობილია თავისი  კონკურსებით,
სადაც მონაწილეობენ პროგრამისტები მსოფლიოს ყველა კუთხიდან. აქ შეგიძლიათ ივარჯიშოთ ამოცანაებზე დამწყები დონიდან ძალიან მოწინავე დონემდე.
Codeforces აქვს მრავალი პროგრამული ენის მხარდაჭერა, მათ შორის: Python, C++, Java, pypy, C#, Free Pascal, Kotlin, Javascript, Node.Js, Go, Delphi და სხვა.
კოდვორსზე შეგიძლიათ სპეციალურ გრაფაში მოათავსოთ თქვენი კოდი და სისტემა მას ავტომატყრად გატესტავს. ამის შედეგად თქვენ ან წარამტებით გაატარებთ ამოცანას ას ჩაგეწრებად
რისი მიზეზიც შეიზლება არასწორი პასუხის დაბრუნება ან დროის / მეხსიერების ლიმიტი იყოს.
