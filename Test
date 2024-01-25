import random

def generate_computer_names(locations, room_numbers, num_pcs):
    computer_names = []

    for location in locations:
        for room_number in room_numbers:
            for pc_number in range(1, num_pcs + 1):
                computer_name = f"{location}_Room{room_number}_PC{pc_number}"
                computer_names.append(computer_name)

    return computer_names

# Example usage
locations = ["Green's Lab"]
room_numbers = [34]
num_pcs = 25

computer_names = generate_computer_names(locations, room_numbers, num_pcs)

# Display generated computer names
for name in computer_names:
    print(name) 
