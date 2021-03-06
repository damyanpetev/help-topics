﻿<!--
|metadata|
{
    "fileName": "igtreegrid-accessibility-compliance",
    "controlName": "igTreeGrid",
    "tags": ["Grids","Section 508"]
}
|metadata|
-->

# Accessibility Compliance (igTreeGrid)

## igTreeGrid Accessibility Compliance

All of the Ignite UI™ controls and components comply with Section 508, Subpart 1194.22 of the Rehabilitation Act of 1973. Table 1 contains the specific rules of Subpart 1194.22 that pertain to the control. Also detailed is how the grid control complies with each rule.

To meet the requirements each accessibility rule, in some cases, you may need to interact with the control by to setting a specific property, but in other cases the control does the work for you.

> **Note:** As jQuery controls are client-only, some of the rules are not supported and are marked as limitations.
 
Table 1: Section 508 compliance description

<table class="table table-striped">
	<tbody>
		<tr>
			<th>Rules</th>
			<th>How We Comply with Rules</th>
		</tr>
		<tr>
			<td>(a)</td>
			<td>A text equivalent for every non-text element shall be provided (e.g., via "alt", "longdesc", or in element content).</td>
		</tr>
		<tr>
			<td>(b)</td>
			<td>Equivalent alternatives for any multimedia presentation shall be synchronized with the presentation.</td>
		</tr>
		<tr>
			<td>(d)*</td>
			<td>The control's markup is not readable without the associated style sheet because it's a client-side control and depends on the CSS rules.</td>
		</tr>
		<tr>
			<td>(g)</td>
			<td>Row and column headers shall be identified for data tables.</td>
		</tr>
		<tr>
			<td>(h)</td>
			<td>Markup shall be used to associate data cells and header cells for data tables that have two or more logical levels of row or column headers.</td>
		</tr>
		<tr>
			<td>(n)*</td>
			<td>The igTreeGrid control participates in the tab sequence of the page and receives focus including via a mouse click. Selection must be enabled in order keyboard navigation to work.<ul>
					<li>LEFT ARROW: When a cell is selected, this command makes the previous cell selected.</li>
					<li>RIGHT ARROW: When a cell is selected, this command makes the next cell selected.</li>
					<li>UP ARROW: Makes the row/cell in the previous row selected</li>
					<li>DOWN ARROW: Makes the row/cell in the next row selected</li>
					<li>SHIFT+UP (or DOWN) ARROW: Includes the above (or below) row/cell in a multiple selection</li>
					<li>CTRL+UP (or DOWN) ARROW: Changes the currently active row/cell</li>
					<li>SHIFT+ENTER: Deselects the currently selected row/cell</li>
				</ul>* Descriptive label (for) is not provided for the editor input elements as part of the igTreeGridUpdating feature. This makes sense only if the grid's element is a form which is not supported.</td>
		</tr>
	</tbody>
</table>

\* - control limitations
 

 


