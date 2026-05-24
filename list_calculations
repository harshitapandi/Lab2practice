def display_main_menu():
    print("Enter some numers separated by commas (eg. 5,67,32)")

def get_user_input():
    user_input = input()
    user_input = user_input.split(",")

    number_list=[]
    for number_str in user_input:
        number_list.append(float(number_str))
    return (number_list)


def sort_temperature(num_list):
    sorted_list = sorted(num_list)
    return (sorted_list)

def calc_median_temperature(num_list):
    if len(num_list) % 2 == 0:
        mid1 = len(num_list) // 2
        mid2 = mid1 - 1
        median = (num_list[mid1] + num_list[mid2]) / 2
    else:
        mid = len(num_list) // 2
        median = num_list[mid]
    return (median)

def calc_average_temperature(num_list):
    total =sum(num_list)
    average = total / len(num_list)
    return (average)

def calc_min_max_temperature(num_list):
    min_temp = min(num_list)
    max_temp = max(num_list)
    return (min_temp, max_temp)


def main():
    print("ET0735 (DevOps for AIoT) - Lab 2 - Introduction to Python")
    display_main_menu()
    num_list = get_user_input()

        # Calculate and display average
    average = calc_average_temperature(num_list)
    print("Average temperature: " + str(average))

    # Calculate and display min and max
    min_max = calc_min_max_temperature(num_list)
    print("Minimum temperature: " + str(min_max[0]))
    print("Maximum temperature: " + str(min_max[1]))

    # Calculate and display median
    median = calc_median_temperature(num_list)
    print("Median temperature: " + str(median))




if __name__ == "__main__":
    main()
