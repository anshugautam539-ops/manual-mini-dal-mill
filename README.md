# manual-mini-dal-mill
Designed and developed a small-scale pulse processing system using mechanical separation principles
Manual Mini Dal Mill is a small-scale pulse processing system designed to remove husk from grains using mechanical separation principles. This project focuses on cost-effective, low-maintenance, and energy-efficient grain processing suitable for rural and small-scale applications.
The system operates manually without the need for heavy electrical power, making it affordable and easy to use in remote areas.
Objective
To design a low-cost dal processing unit
To perform husk separation using mechanical friction
To improve grain cleaning efficiency
To support small-scale farmers and rural industries

Working Principle
The machine works on the principle of:
Friction and abrasion
Mechanical rotation
Husk separation through controlled pressure
Grains are fed into the rotating chamber where friction removes the outer husk layer. The separated husk is removed through an outlet while clean dal is collected separately.

Major Components
Hopper (grain feeding section)
Rotating drum / abrasive chamber
Shaft and bearing system
Frame structure
Outlet for husk separation

Applications
Small-scale farming units
Rural self-employment projects
Cottage industries
Agricultural processing units
# Manual Mini Dal Mill Efficiency Calculator

def calculate_efficiency(input_weight, output_weight):
    efficiency = (output_weight / input_weight) * 100
    return efficiency

def calculate_loss(input_weight, output_weight):
    loss = input_weight - output_weight
    return loss

# Example values
input_weight = float(input("Enter total grain input (kg): "))
output_weight = float(input("Enter dal output after processing (kg): "))

efficiency = calculate_efficiency(input_weight, output_weight)
loss = calculate_loss(input_weight, output_weight)

print("\n--- Results ---")
print(f"Processing Efficiency: {efficiency:.2f}%")
print(f"Material Loss: {loss:.2f} kg")
