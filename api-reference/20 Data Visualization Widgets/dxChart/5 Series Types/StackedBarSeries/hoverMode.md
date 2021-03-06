---
id: dxChartSeriesTypes.StackedBarSeries.hoverMode
acceptValues: 'onlyPoint' | 'allSeriesPoints' | 'allArgumentPoints' | 'none'
type: String
default: 'onlyPoint'
---
---
##### shortDescription
Specifies series elements to be highlighted when a user points to a series.

---
When a user points to a series, it may react in one of the following ways depending on the value of the **hoverMode** option.

<table class="dx-table">
    <tr>
        <th>hoverMode</th>
        <th>Result</th>
    </tr>
    <tr>
        <td><i>"onlyPoint"</i></td>
        <td><img src="/Content/images/doc/20_1/ChartJS/hoverMode/series/stackedbar/onlyPoint.png" /></td>
    </tr>
    <tr>
        <td><i>"allSeriesPoints"</i></td>
        <td><img src="/Content/images/doc/20_1/ChartJS/hoverMode/series/stackedbar/allSeriesPoints.png" /></td>
    </tr>
    <tr>
        <td><i>"allArgumentPoints"</i></td>
        <td><img src="/Content/images/doc/20_1/ChartJS/hoverMode/series/stackedbar/allArgumentPoints.png" /></td>
    </tr>
    <tr>
        <td><i>"none"</i></td>
        <td><img src="/Content/images/doc/20_1/ChartJS/hoverMode/series/stackedbar/none.png" /></td>
    </tr>
</table>

#include common-ref-enum with {
    enum: "`ChartSeriesHoverMode`",
    values: "`OnlyPoint`, `AllSeriesPoints`, `AllArgumentPoints`, and `None`"
} Note that although this enum accepts more values, only the listed ones can be applied to a stacked bar series.

#####See Also#####
- [hoverStyle](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/hoverStyle '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/StackedBarSeries/hoverStyle/') - specifies the appearance of series in the hover state.