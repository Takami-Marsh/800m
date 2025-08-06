# 800m 4-Week Training Block Planner

A comprehensive web application for generating personalized 4-week training blocks for 800m runners. This tool creates structured training plans based on your current fitness level, weekly mileage, and training intensity preferences.

## Features

- **Personalized Training Plans**: Generate customized 4-week training blocks based on your 800m PR and current weekly mileage
- **Multiple Training Intensities**: Choose from Easy, Normal, or Hard training loads
- **Comprehensive Workout Library**: Access a wide variety of workouts including:
  - Aerobic development (recovery runs, long runs, progression runs)
  - Threshold training (tempo runs, threshold intervals)
  - VO₂max development (classic intervals, ladder workouts)
  - Speed and race-specific training (pace work, simulations)
  - Supplementary work (plyometrics, strength, mobility)
- **Interactive Workout Details**: Click on any workout to see detailed explanations, purposes, and benefits
- **Training Load Visualization**: Visual chart showing weekly mileage and training load progression
- **Plan Management**: Save, load, and manage multiple training plans
- **Athlete Profile**: Automatically saves your profile settings for future use
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## How to Use

1. **Set Your Profile**: Enter your 800m PR and current weekly mileage
2. **Choose Training Intensity**: Select from Easy, Normal, or Hard based on your experience and goals
3. **Generate Plan**: Click "Generate New Plan" to create your 4-week training block
4. **Review Your Plan**: Examine the daily workouts, weekly mileage, and training load
5. **Save Your Plan**: Save the plan for future reference or download as JSON

## Training Structure

The 4-week block follows a progressive structure:

- **Weeks 1-3**: Progressive loading with increasing mileage and intensity
- **Week 4**: Reduced mileage (70%) for recovery and adaptation
- **Daily Structure**: 
  - AM sessions focus on aerobic development
  - PM sessions focus on speed, power, and race-specific work
  - Two plyometrics sessions per week (non-consecutive days)
  - Sunday as full recovery day

## Workout Categories

### AM Sessions (Aerobic Focus)
- **Easy**: Recovery runs, long runs, progression runs
- **Tempo**: Threshold development intervals and continuous runs
- **VO₂max**: High-intensity intervals for maximal oxygen uptake

### PM Sessions (Speed/Power Focus)
- **Speed**: Neuromuscular development, hill sprints, acceleration work
- **Race**: 800m-specific pace work and simulations
- **Endurance**: Speed endurance and lactate tolerance development
- **Supplementary**: Plyometrics, strength training, mobility work

## Pace Zones

The calculator automatically determines your training paces based on your 800m PR:
- **Easy**: Recovery & Base Building (53% of race speed)
- **Steady**: Aerobic Development (60% of race speed)
- **Threshold**: Lactate Threshold (65% of race speed)
- **VO₂max**: VO₂ Max Development (75% of race speed)
- **Race**: 800m Race Pace (100% of race speed)
- **Speed**: Neuromuscular Power (110% of race speed)

## Technical Details

- **Built with**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Bootstrap 5 with custom neumorphic design
- **Charts**: Chart.js for training load visualization
- **Storage**: Local browser storage for plan persistence
- **Responsive**: Mobile-friendly design with touch support

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Privacy

All training data is stored locally in your browser. No data is sent to external servers or cloud services.

## Contributing

This is a personal project for the running community. Feel free to use, modify, and share the tool to help other 800m runners improve their training.

## License

This project is open source and available under the MIT License.
