# python-kullan-c-giri-python-login-design-

user = raw_input('Create Username: ')
password = raw_input('Create Password: ')
store_user =[roger, Jon]
store_pass =[tennis, soccer]

store_user.append(user)
store_pass.append(password)

if user in store_user:
    print "That user already exsist"

while 1 == 1:
    userguess=""
    passwordguess=""
    key=""
    while (userguess != user) or (passwordguess != password):
        userguess = raw_input('User Name: ')
        passwordguess = raw_input('Password:')

    print "Welcome,",user, ". Type Lock to Lock or Type Create to create another user."
    print store_user
    print store_pass

    while key != "lock":
        key = raw_input("")
