%% Increase the scale for better visibility on web pages
%% Change `scale` value as needed
%% This could go to a 1.5 or even higher depending on desired zoom level

%% Wrap entire flowchart with graph directive with scaling
graph TD
classDef onPushClass fill:#095,stroke:#333,stroke-width:4px;

%% Define the scale for the chart
%% Scale set to 2 for larger view
style diagram scale=2

AppComponent-245[AppComponent]-->PortalComponent-246[PortalComponent]
PortalComponent-246[PortalComponent]-->HeaderComponent-247[HeaderComponent]
HeaderComponent-247[HeaderComponent]-->MatToolbar-248[MatToolbar]
MatToolbar-248[MatToolbar]-->MatLegacyTabNav-249[MatLegacyTabNav]
MatToolbar-248[MatToolbar]-->MatLegacyButton-250[MatLegacyButton]
MatToolbar-248[MatToolbar]-->MatLegacyMenu-251[MatLegacyMenu]
PortalComponent-246[PortalComponent]-->ProjectsWrapperComponent-252[ProjectsWrapperComponent]
ProjectsWrapperComponent-252[ProjectsWrapperComponent]-->MapWrapperComponent-253[MapWrapperComponent]
MapWrapperComponent-253[MapWrapperComponent]-->ProjectsLocationMapComponent-254[ProjectsLocationMapComponent]
ProjectsLocationMapComponent-254[ProjectsLocationMapComponent]-->EsriMapComponent-255[EsriMapComponent]
MapWrapperComponent-253[MapWrapperComponent]-->MatIcon-256[MatIcon]
MapWrapperComponent-253[MapWrapperComponent]-->MatIcon-257[MatIcon]
MapWrapperComponent-253[MapWrapperComponent]-->MatIcon-258[MatIcon]
ProjectsWrapperComponent-252[ProjectsWrapperComponent]-->MatIcon-259[MatIcon]
ProjectsWrapperComponent-252[ProjectsWrapperComponent]-->ProjectsPageComponent-260[ProjectsPageComponent]
ProjectsPageComponent-260[ProjectsPageComponent]-->MatIcon-261[MatIcon]
ProjectsPageComponent-260[ProjectsPageComponent]-->MatLegacyMenu-262[MatLegacyMenu]
ProjectsPageComponent-260[ProjectsPageComponent]-->ProjectCardComponent-263[ProjectCardComponent]
ProjectCardComponent-263[ProjectCardComponent]-->ContractProgressCardComponent-264[ContractProgressCardComponent]
ProjectCardComponent-263[ProjectCardComponent]-->ContractProgressCardComponent-265[ContractProgressCardComponent]
ProjectCardComponent-263[ProjectCardComponent]-->MatIcon-266[MatIcon]
ProjectCardComponent-263[ProjectCardComponent]-->MatLegacyMenu-267[MatLegacyMenu]
ProjectCardComponent-263[ProjectCardComponent]-->IssuesSummaryComponent-268[IssuesSummaryComponent]
IssuesSummaryComponent-268[IssuesSummaryComponent]-->MatIcon-269[MatIcon]
IssuesSummaryComponent-268[IssuesSummaryComponent]-->MatIcon-270[MatIcon]
ProjectCardComponent-263[ProjectCardComponent]-->StatusSummaryComponent-271[StatusSummaryComponent]
ProjectsPageComponent-260[ProjectsPageComponent]-->ProjectCardComponent-272[ProjectCardComponent]
ProjectCardComponent-272[ProjectCardComponent]-->ContractProgressCardComponent-273[ContractProgressCardComponent]
ProjectCardComponent-272[ProjectCardComponent]-->ContractProgressCardComponent-274[ContractProgressCardComponent]
ProjectCardComponent-272[ProjectCardComponent]-->MatIcon-275[MatIcon]
ProjectCardComponent-272[ProjectCardComponent]-->MatLegacyMenu-276[MatLegacyMenu]
ProjectCardComponent-272[ProjectCardComponent]-->IssuesSummaryComponent-277[IssuesSummaryComponent]
IssuesSummaryComponent-277[IssuesSummaryComponent]-->MatIcon-278[MatIcon]
IssuesSummaryComponent-277[IssuesSummaryComponent]-->MatIcon-279[MatIcon]
ProjectCardComponent-272[ProjectCardComponent]-->StatusSummaryComponent-280[StatusSummaryComponent]
ProjectsPageComponent-260[ProjectsPageComponent]-->ProjectCardComponent-281[ProjectCardComponent]
ProjectCardComponent-281[ProjectCardComponent]-->ContractProgressCardComponent-282[ContractProgressCardComponent]
ProjectCardComponent-281[ProjectCardComponent]-->ContractProgressCardComponent-283[ContractProgressCardComponent]
ProjectCardComponent-281[ProjectCardComponent]-->MatIcon-284[MatIcon]
ProjectCardComponent-281[ProjectCardComponent]-->MatLegacyMenu-285[MatLegacyMenu]
ProjectCardComponent-281[ProjectCardComponent]-->IssuesSummaryComponent-286[IssuesSummaryComponent]
IssuesSummaryComponent-286[IssuesSummaryComponent]-->MatIcon-287[MatIcon]
IssuesSummaryComponent-286[IssuesSummaryComponent]-->MatIcon-288[MatIcon]
ProjectCardComponent-281[ProjectCardComponent]-->StatusSummaryComponent-289[StatusSummaryComponent]
ProjectsPageComponent-260[ProjectsPageComponent]-->PaginatorComponent-290[PaginatorComponent]
PaginatorComponent-290[PaginatorComponent]-->MatIcon-291[MatIcon]
PaginatorComponent-290[PaginatorComponent]-->MatIcon-292[MatIcon]
PortalComponent-246[PortalComponent]-->FooterComponent-293[FooterComponent]
class MatToolbar-248,MatLegacyButton-250,MatLegacyMenu-251,MatIcon-256,MatIcon-257,MatIcon-258,MatIcon-259,MatIcon-261,MatLegacyMenu-262,MatIcon-266,MatLegacyMenu-267,MatIcon-269,MatIcon-270,MatIcon-275,MatLegacyMenu-276,MatIcon-278,MatIcon-279,MatIcon-284,MatLegacyMenu-285,MatIcon-287,MatIcon-288,MatIcon-291,MatIcon-292 onPushClass
