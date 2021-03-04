# Hrynko Dzianis

#### email: ut.scorpion@mail.ru

***
During this course, I'd like to learn JavaScripts as progressive language. I'm already a software developer and the main language I use it's PHP. I think it'd great to learn also JS, and after that ReactJS.
***
**I have skill in:**
* PHP
* JS
* HTML
* MySQL
* GIT
* etc.

```
public function update(Request $request, int $itemId)
    {
        $location = $this->entityManager->find(Location::class, $itemId);

        if (!isset($location)) {
            throw new Http400ApiException();
        }

        $validatorResponse = $this->validator->validate($request->all());

        if ($validatorResponse === true) {
            $location->setNumbersCount($request->input('numbers_count'));

            $this->entityManager->persist($location);
            $this->entityManager->flush();
        }
    }
```
***

**I'm a middle developer** in an outsource company. 

I've finished courese at [istep.by](https://itstep.by/) as Full Stack developer

***
My English level is Intermediate+