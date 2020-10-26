5.10
current_users = ['Alex', 'Olia', 'Ilia', 'Max', 'Bob']
current_users_copy = []
for current_user in current_users:
	current_users_copy.append(current_user.lower())
new_users = ['Vadim', 'Olia', 'Ilia', 'Mark', 'Oliver']
for new_user in new_users:
	if new_user.lower() in current_users_copy:
		print(f"Name {new_user} is busy, choose different name.")
	else:
		print(f"Name {new_user} available.")