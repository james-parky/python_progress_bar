# Custom terminal progress bar in python

## Import

    from progress_bar import ProgressBar

## Usage

    <bar1> = ProgressBar(increment=1, target=100, annotation=True, percentage=50)

    increment: The value that each section of the bar is worth. (Integer from [1, 2, 5]) (Default value of 2)

    target: The target percentage to be displayed in red. (Integer in the range 0-100) (Default value of 100)

    annotation: Should the current percentage also be displayed. (Boolean) (Default value of True)

    percentage: The current percentage that the bar is filled. (Integer / Float) (Default value of 0)

## Notes

    Values are always rounded down to the nearest increment multiple.
    For example, a target value of 63, given an increment value of 5, would round to 60.
