# phone_number
Validates phone numbers and returns a list of numbers or string  with +254 prefix

##Dependecies
Tested in python 2.4 to python 2.7.9

## Installation
Clone the project

## Usage
1. from phonenumber import PhoneNumber
2. phn = PhoneNumber("07XXXXXXXX")
3. phone = phn.valid_numbers()
4. number_list = [7XXXXXXXXX, "07XXXXXXXX", "7XXXXXXXXX"]
5. valid_list = PhoneNumber(number_list)
6. valid_list = valid_list.valid_numbers()

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
