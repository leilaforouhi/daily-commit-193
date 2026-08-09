
def sum_even_positions(numbers):
    return sum(
        number for index, number in enumerate(numbers)
        if index % 2 == 0
    )


if __name__ == "__main__":
    values = [10, 20, 30, 40, 50, 60]

    print(f"Numbers: {values}")
    print(f"Sum of even positions: {sum_even_positions(values)}")
