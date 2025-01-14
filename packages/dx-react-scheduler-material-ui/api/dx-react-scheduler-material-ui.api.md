## API Report File for "@devexpress/dx-react-scheduler-material-ui"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { AllDayPanel as AllDayPanel_2 } from '@devexpress/dx-react-scheduler';
import { AppointmentForm as AppointmentForm_2 } from '@devexpress/dx-react-scheduler';
import { AppointmentMeta } from '@devexpress/dx-react-scheduler';
import { AppointmentModel } from '@devexpress/dx-react-scheduler';
import { Appointments as Appointments_2 } from '@devexpress/dx-react-scheduler';
import { AppointmentTooltip as AppointmentTooltip_2 } from '@devexpress/dx-react-scheduler';
import { ConfirmationDialog as ConfirmationDialog_2 } from '@devexpress/dx-react-scheduler';
import { CurrentTimeIndicator as CurrentTimeIndicator_2 } from '@devexpress/dx-react-scheduler';
import { DateNavigator as DateNavigator_2 } from '@devexpress/dx-react-scheduler';
import { DayView as DayView_2 } from '@devexpress/dx-react-scheduler';
import { DragDropProvider as DragDropProvider_2 } from '@devexpress/dx-react-scheduler';
import { EditRecurrenceMenu as EditRecurrenceMenu_2 } from '@devexpress/dx-react-scheduler';
import { GroupingPanel as GroupingPanel_2 } from '@devexpress/dx-react-scheduler';
import { MonthView as MonthView_2 } from '@devexpress/dx-react-scheduler';
import { Palette } from '@devexpress/dx-react-scheduler';
import * as React_2 from 'react';
import { Resource } from '@devexpress/dx-react-scheduler';
import { Scheduler as Scheduler_2 } from '@devexpress/dx-react-scheduler';
import { TodayButton as TodayButton_2 } from '@devexpress/dx-react-scheduler';
import { Toolbar as Toolbar_2 } from '@devexpress/dx-react-scheduler';
import { ViewSwitcher as ViewSwitcher_2 } from '@devexpress/dx-react-scheduler';
import { WeekView as WeekView_2 } from '@devexpress/dx-react-scheduler';

// @public (undocumented)
export namespace AllDayPanel {
  export type CellData = AllDayPanel_2.CellData;
}

// @public (undocumented)
export namespace AllDayPanel {
  export type LayoutProps = AllDayPanel_2.LayoutProps;
}

// @public (undocumented)
export namespace AllDayPanel {
  export type CellProps = AllDayPanel_2.CellProps;
}

// @public (undocumented)
export namespace AllDayPanel {
  export type RowProps = AllDayPanel_2.RowProps;
}

// @public (undocumented)
export namespace AllDayPanel {
  export type TitleCellProps = AllDayPanel_2.TitleCellProps;
}

// @public (undocumented)
export namespace AllDayPanel {
  export type AppointmentLayerProps = AllDayPanel_2.AppointmentLayerProps;
}

// @public (undocumented)
export namespace AllDayPanel {
  export type ContainerProps = AllDayPanel_2.ContainerProps;
}

// @public
export const AllDayPanel: React_2.ComponentType<AllDayPanelProps> & {
  Layout: React_2.ComponentType<AllDayPanel_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Cell: React_2.ComponentType<AllDayPanel_2.CellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Row: React_2.ComponentType<AllDayPanel_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TitleCell: React_2.ComponentType<AllDayPanel_2.TitleCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  AppointmentLayer: React_2.ComponentType<AllDayPanel_2.AppointmentLayerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Container: React_2.ComponentType<AllDayPanel_2.ContainerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface AllDayPanelProps {
  appointmentLayerComponent?: React_2.ComponentType<AllDayPanel_2.AppointmentLayerProps>;
  cellComponent?: React_2.ComponentType<AllDayPanel_2.CellProps>;
  containerComponent?: React_2.ComponentType<AllDayPanel_2.ContainerProps>;
  layoutComponent?: React_2.ComponentType<AllDayPanel_2.LayoutProps>;
  messages?: AllDayPanel_2.LocalizationMessages;
  rowComponent?: React_2.ComponentType<AllDayPanel_2.RowProps>;
  titleCellComponent?: React_2.ComponentType<AllDayPanel_2.TitleCellProps>;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type OverlayProps = AppointmentForm_2.OverlayProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type LayoutProps = AppointmentForm_2.LayoutProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type CommandLayoutProps = AppointmentForm_2.CommandLayoutProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type BasicLayoutProps = AppointmentForm_2.BasicLayoutProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type RecurrenceLayoutProps = AppointmentForm_2.RecurrenceLayoutProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type BooleanEditorProps = AppointmentForm_2.BooleanEditorProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type CommandButtonProps = AppointmentForm_2.CommandButtonProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type DateEditorProps = AppointmentForm_2.DateEditorProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type LabelProps = AppointmentForm_2.LabelProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type RadioGroupProps = AppointmentForm_2.RadioGroupProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type SelectProps = AppointmentForm_2.SelectProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type ResourceEditorProps = AppointmentForm_2.ResourceEditorProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type TextEditorProps = AppointmentForm_2.TextEditorProps;
}

// @public (undocumented)
export namespace AppointmentForm {
  export type WeeklyRecurrenceSelectorProps = AppointmentForm_2.WeeklyRecurrenceSelectorProps;
}

// @public
export const AppointmentForm: React_2.ComponentType<AppointmentFormProps> & {
  Overlay: React_2.ComponentType<AppointmentForm_2.OverlayProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Layout: React_2.ComponentType<AppointmentForm_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  CommandLayout: React_2.ComponentType<AppointmentForm_2.CommandLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  BasicLayout: React_2.ComponentType<AppointmentForm_2.BasicLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  RecurrenceLayout: React_2.ComponentType<AppointmentForm_2.RecurrenceLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TextEditor: React_2.ComponentType<AppointmentForm_2.TextEditorProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DateEditor: React_2.ComponentType<AppointmentForm_2.DateEditorProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Label: React_2.ComponentType<AppointmentForm_2.LabelProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  BooleanEditor: React_2.ComponentType<AppointmentForm_2.BooleanEditorProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Select: React_2.ComponentType<AppointmentForm_2.SelectProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  RadioGroup: React_2.ComponentType<AppointmentForm_2.RadioGroupProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  WeeklyRecurrenceSelector: React_2.ComponentType<AppointmentForm_2.WeeklyRecurrenceSelectorProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface AppointmentFormProps {
  appointmentData?: AppointmentModel;
  basicLayoutComponent?: React_2.ComponentType<AppointmentForm_2.BasicLayoutProps>;
  booleanEditorComponent?: React_2.ComponentType<AppointmentForm_2.BooleanEditorProps>;
  commandButtonComponent?: React_2.ComponentType<AppointmentForm_2.CommandButtonProps>;
  commandLayoutComponent?: React_2.ComponentType<AppointmentForm_2.CommandLayoutProps>;
  dateEditorComponent?: React_2.ComponentType<AppointmentForm_2.DateEditorProps>;
  labelComponent?: React_2.ComponentType<AppointmentForm_2.LabelProps>;
  layoutComponent?: React_2.ComponentType<AppointmentForm_2.LayoutProps>;
  messages?: AppointmentForm_2.LocalizationMessages;
  onAppointmentDataChange?: (appointmentData: AppointmentModel) => void;
  onVisibilityChange?: (visible: boolean) => void;
  overlayComponent?: React_2.ComponentType<AppointmentForm_2.OverlayProps>;
  radioGroupComponent?: React_2.ComponentType<AppointmentForm_2.RadioGroupProps>;
  readOnly?: boolean;
  recurrenceLayoutComponent?: React_2.ComponentType<AppointmentForm_2.RecurrenceLayoutProps>;
  resourceEditorComponent?: React_2.ComponentType<AppointmentForm_2.ResourceEditorProps>;
  selectComponent?: React_2.ComponentType<AppointmentForm_2.SelectProps>;
  textEditorComponent?: React_2.ComponentType<AppointmentForm_2.TextEditorProps>;
  visible?: boolean;
  weeklyRecurrenceSelectorComponent?: React_2.ComponentType<AppointmentForm_2.WeeklyRecurrenceSelectorProps>;
}

// @public (undocumented)
export namespace Appointments {
  export type AppointmentProps = Appointments_2.AppointmentProps;
}

// @public (undocumented)
export namespace Appointments {
  export type AppointmentContentProps = Appointments_2.AppointmentContentProps;
}

// @public (undocumented)
export namespace Appointments {
  export type SplitIndicatorProps = Appointments_2.SplitIndicatorProps;
}

// @public (undocumented)
export namespace Appointments {
  export type ContainerProps = Appointments_2.ContainerProps;
}

// @public
export const Appointments: React_2.ComponentType<AppointmentsProps> & {
  Appointment: React_2.ComponentType<Appointments_2.AppointmentProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  AppointmentContent: React_2.ComponentType<Appointments_2.AppointmentContentProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  SplitIndicator: React_2.ComponentType<Appointments_2.SplitIndicatorProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Container: React_2.ComponentType<Appointments_2.ContainerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface AppointmentsProps {
  appointmentComponent?: React_2.ComponentType<Appointments_2.AppointmentProps>;
  appointmentContentComponent?: React_2.ComponentType<Appointments_2.AppointmentContentProps>;
  containerComponent?: React_2.ComponentType<Appointments_2.ContainerProps>;
  recurringIconComponent?: React_2.ComponentType<object>;
  splitIndicatorComponent?: React_2.ComponentType<Appointments_2.SplitIndicatorProps>;
}

// @public (undocumented)
export namespace AppointmentTooltip {
  export type LayoutProps = AppointmentTooltip_2.LayoutProps;
}

// @public (undocumented)
export namespace AppointmentTooltip {
  export type HeaderProps = AppointmentTooltip_2.HeaderProps;
}

// @public (undocumented)
export namespace AppointmentTooltip {
  export type ContentProps = AppointmentTooltip_2.ContentProps;
}

// @public (undocumented)
export namespace AppointmentTooltip {
  export type CommandButtonProps = AppointmentTooltip_2.CommandButtonProps;
}

// @public
export const AppointmentTooltip: React_2.ComponentType<AppointmentTooltipProps> & {
  Layout: React_2.ComponentType<AppointmentTooltip_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Header: React_2.ComponentType<AppointmentTooltip_2.HeaderProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Content: React_2.ComponentType<AppointmentTooltip_2.ContentProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  CommandButton: React_2.ComponentType<AppointmentTooltip_2.CommandButtonProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface AppointmentTooltipProps {
  appointmentMeta?: AppointmentMeta;
  commandButtonComponent?: React_2.ComponentType<AppointmentTooltip_2.CommandButtonProps>;
  contentComponent?: React_2.ComponentType<AppointmentTooltip_2.ContentProps>;
  headerComponent?: React_2.ComponentType<AppointmentTooltip_2.HeaderProps>;
  layoutComponent?: React_2.ComponentType<AppointmentTooltip_2.LayoutProps>;
  onAppointmentMetaChange?: (appointmentMeta: AppointmentMeta) => void;
  onVisibilityChange?: (visible: boolean) => void;
  recurringIconComponent?: React_2.ComponentType<object>;
  showCloseButton?: boolean;
  showDeleteButton?: boolean;
  showOpenButton?: boolean;
  visible?: boolean;
}

// @public (undocumented)
export namespace ConfirmationDialog {
  export type LayoutProps = ConfirmationDialog_2.LayoutProps;
}

// @public (undocumented)
export namespace ConfirmationDialog {
  export type OverlayProps = ConfirmationDialog_2.OverlayProps;
}

// @public (undocumented)
export namespace ConfirmationDialog {
  export type ButtonProps = ConfirmationDialog_2.ButtonProps;
}

// @public
export const ConfirmationDialog: React_2.ComponentType<ConfirmationDialogProps> & {
  Layout: React_2.ComponentType<ConfirmationDialog_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Overlay: React_2.ComponentType<ConfirmationDialog_2.OverlayProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Button: React_2.ComponentType<ConfirmationDialog_2.ButtonProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface ConfirmationDialogProps {
  buttonComponent?: React_2.ComponentType<ConfirmationDialog_2.ButtonProps>;
  ignoreCancel?: boolean;
  ignoreDelete?: boolean;
  layoutComponent?: React_2.ComponentType<ConfirmationDialog_2.LayoutProps>;
  messages?: ConfirmationDialog_2.LocalizationMessages;
  overlayComponent?: React_2.ComponentType<ConfirmationDialog_2.OverlayProps>;
}

// @public (undocumented)
export namespace CurrentTimeIndicator {
  export type IndicatorProps = CurrentTimeIndicator_2.IndicatorProps;
}

// @public
export const CurrentTimeIndicator: React_2.ComponentType<CurrentTimeIndicatorProps> & {
  Indicator: React_2.ComponentType<CurrentTimeIndicator_2.IndicatorProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface CurrentTimeIndicatorProps {
  indicatorComponent?: React_2.ComponentType<CurrentTimeIndicator_2.IndicatorProps>;
  shadePreviousAppointments?: boolean;
  shadePreviousCells?: boolean;
  updateInterval?: number;
}

// @public (undocumented)
export namespace DateNavigator {
  export type RootProps = DateNavigator_2.RootProps;
}

// @public (undocumented)
export namespace DateNavigator {
  export type OverlayProps = DateNavigator_2.OverlayProps;
}

// @public (undocumented)
export namespace DateNavigator {
  export type OpenButtonProps = DateNavigator_2.OpenButtonProps;
}

// @public (undocumented)
export namespace DateNavigator {
  export type NavigationButtonProps = DateNavigator_2.NavigationButtonProps;
}

// @public
export const DateNavigator: React_2.ComponentType<DateNavigatorProps> & {
  Root: React_2.ComponentType<DateNavigator_2.RootProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Overlay: React_2.ComponentType<DateNavigator_2.OverlayProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  OpenButton: React_2.ComponentType<DateNavigator_2.OpenButtonProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  NavigationButton: React_2.ComponentType<DateNavigator_2.NavigationButtonProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface DateNavigatorProps {
  navigationButtonComponent?: React_2.ComponentType<DateNavigator_2.NavigationButtonProps>;
  openButtonComponent?: React_2.ComponentType<DateNavigator_2.OpenButtonProps>;
  overlayComponent?: React_2.ComponentType<DateNavigator_2.OverlayProps>;
  rootComponent?: React_2.ComponentType<DateNavigator_2.RootProps>;
}

// @public (undocumented)
export namespace DayView {
  export type CellData = DayView_2.CellData;
}

// @public (undocumented)
export namespace DayView {
  export type LayoutProps = DayView_2.LayoutProps;
}

// @public (undocumented)
export namespace DayView {
  export type TimeScaleLayoutProps = DayView_2.TimeScaleLayoutProps;
}

// @public (undocumented)
export namespace DayView {
  export type TimeScaleLabelProps = DayView_2.TimeScaleLabelProps;
}

// @public (undocumented)
export namespace DayView {
  export type TimeScaleTickCellProps = DayView_2.TimeScaleTickCellProps;
}

// @public (undocumented)
export namespace DayView {
  export type DayScaleLayoutProps = DayView_2.DayScaleLayoutProps;
}

// @public (undocumented)
export namespace DayView {
  export type DayScaleCellProps = DayView_2.DayScaleCellProps;
}

// @public (undocumented)
export namespace DayView {
  export type DayScaleEmptyCellProps = DayView_2.DayScaleEmptyCellProps;
}

// @public (undocumented)
export namespace DayView {
  export type TimeTableLayoutProps = DayView_2.TimeTableLayoutProps;
}

// @public (undocumented)
export namespace DayView {
  export type TimeTableCellProps = DayView_2.TimeTableCellProps;
}

// @public (undocumented)
export namespace DayView {
  export type AppointmentLayerProps = DayView_2.AppointmentLayerProps;
}

// @public (undocumented)
export namespace DayView {
  export type RowProps = DayView_2.RowProps;
}

// @public
export const DayView: React_2.ComponentType<DayViewProps> & {
  Layout: React_2.ComponentType<DayView_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeScaleLayout: React_2.ComponentType<DayView_2.TimeScaleLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeScaleLabel: React_2.ComponentType<DayView_2.TimeScaleLabelProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeScaleTickCell: React_2.ComponentType<DayView_2.TimeScaleTickCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleLayout: React_2.ComponentType<DayView_2.DayScaleLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleCell: React_2.ComponentType<DayView_2.DayScaleCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleRow: React_2.ComponentType<DayView_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleEmptyCell: React_2.ComponentType<DayView_2.DayScaleEmptyCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableLayout: React_2.ComponentType<DayView_2.TimeTableLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableCell: React_2.ComponentType<DayView_2.TimeTableCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableRow: React_2.ComponentType<DayView_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  AppointmentLayer: React_2.ComponentType<DayView_2.AppointmentLayerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface DayViewProps {
  appointmentLayerComponent?: React_2.ComponentType<DayView_2.AppointmentLayerProps>;
  cellDuration?: number;
  dayScaleCellComponent?: React_2.ComponentType<DayView_2.DayScaleCellProps>;
  dayScaleEmptyCellComponent?: React_2.ComponentType<DayView_2.DayScaleEmptyCellProps>;
  dayScaleLayoutComponent?: React_2.ComponentType<DayView_2.DayScaleLayoutProps>;
  dayScaleRowComponent?: React_2.ComponentType<DayView_2.RowProps>;
  displayName?: string;
  endDayHour?: number;
  intervalCount?: number;
  layoutComponent?: React_2.ComponentType<DayView_2.LayoutProps>;
  name?: string;
  startDayHour?: number;
  timeScaleLabelComponent?: React_2.ComponentType<DayView_2.TimeScaleLabelProps>;
  timeScaleLayoutComponent?: React_2.ComponentType<DayView_2.TimeScaleLayoutProps>;
  timeScaleTickCellComponent?: React_2.ComponentType<DayView_2.TimeScaleTickCellProps>;
  timeTableCellComponent?: React_2.ComponentType<DayView_2.TimeTableCellProps>;
  timeTableLayoutComponent?: React_2.ComponentType<DayView_2.TimeTableLayoutProps>;
  timeTableRowComponent?: React_2.ComponentType<DayView_2.RowProps>;
}

// @public (undocumented)
export namespace DragDropProvider {
  export type DraftAppointmentProps = DragDropProvider_2.DraftAppointmentProps;
}

// @public (undocumented)
export namespace DragDropProvider {
  export type SourceAppointmentProps = DragDropProvider_2.SourceAppointmentProps;
}

// @public (undocumented)
export namespace DragDropProvider {
  export type ResizeProps = DragDropProvider_2.ResizeProps;
}

// @public (undocumented)
export namespace DragDropProvider {
  export type ContainerProps = DragDropProvider_2.ContainerProps;
}

// @public
export const DragDropProvider: React_2.ComponentType<DragDropProviderProps> & {
  DraftAppointment: React_2.ComponentType<DragDropProvider_2.DraftAppointmentProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  SourceAppointment: React_2.ComponentType<DragDropProvider_2.SourceAppointmentProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Resize: React_2.ComponentType<DragDropProvider_2.ResizeProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Container: React_2.ComponentType<DragDropProvider_2.ContainerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface DragDropProviderProps {
  allowDrag?: (appointmentData: AppointmentModel) => boolean;
  allowResize?: (appointmentData: AppointmentModel) => boolean;
  containerComponent?: React_2.ComponentType<DragDropProvider_2.ContainerProps>;
  draftAppointmentComponent?: React_2.ComponentType<DragDropProvider_2.DraftAppointmentProps>;
  resizeComponent?: React_2.ComponentType<DragDropProvider_2.ResizeProps>;
  scrollSpeed?: number;
  sourceAppointmentComponent?: React_2.ComponentType<DragDropProvider_2.SourceAppointmentProps>;
}

// @public (undocumented)
export namespace EditRecurrenceMenu {
  export type LayoutProps = EditRecurrenceMenu_2.LayoutProps;
}

// @public (undocumented)
export namespace EditRecurrenceMenu {
  export type OverlayProps = EditRecurrenceMenu_2.OverlayProps;
}

// @public (undocumented)
export namespace EditRecurrenceMenu {
  export type ButtonProps = EditRecurrenceMenu_2.ButtonProps;
}

// @public
export const EditRecurrenceMenu: React_2.ComponentType<EditRecurrenceMenuProps> & {
  Layout: React_2.ComponentType<EditRecurrenceMenu_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Overlay: React_2.ComponentType<EditRecurrenceMenu_2.OverlayProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Button: React_2.ComponentType<EditRecurrenceMenu_2.ButtonProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface EditRecurrenceMenuProps {
  buttonComponent?: React_2.ComponentType<EditRecurrenceMenu_2.ButtonProps>;
  layoutComponent?: React_2.ComponentType<EditRecurrenceMenu_2.LayoutProps>;
  messages?: EditRecurrenceMenu_2.LocalizationMessages;
  overlayComponent?: React_2.ComponentType<EditRecurrenceMenu_2.OverlayProps>;
}

// @public (undocumented)
export namespace GroupingPanel {
  export type HorizontalLayoutProps = GroupingPanel_2.HorizontalLayoutProps;
}

// @public (undocumented)
export namespace GroupingPanel {
  export type VerticalLayoutProps = GroupingPanel_2.VerticalLayoutProps;
}

// @public (undocumented)
export namespace GroupingPanel {
  export type RowProps = GroupingPanel_2.RowProps;
}

// @public (undocumented)
export namespace GroupingPanel {
  export type CellProps = GroupingPanel_2.CellProps;
}

// @public
export const GroupingPanel: React_2.ComponentType<GroupingPanelProps> & {
  HorizontalLayout: React_2.ComponentType<GroupingPanel_2.HorizontalLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  VerticalLayout: React_2.ComponentType<GroupingPanel_2.VerticalLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Row: React_2.ComponentType<GroupingPanel_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  Cell: React_2.ComponentType<GroupingPanel_2.CellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface GroupingPanelProps {
  cellComponent?: React_2.ComponentType<GroupingPanel_2.CellProps>;
  horizontalLayoutComponent?: React_2.ComponentType<GroupingPanel_2.HorizontalLayoutProps>;
  rowComponent?: React_2.ComponentType<GroupingPanel_2.RowProps>;
  verticalLayoutComponent?: React_2.ComponentType<GroupingPanel_2.HorizontalLayoutProps>;
}

// @public (undocumented)
export namespace MonthView {
  export type CellData = MonthView_2.CellData;
}

// @public (undocumented)
export namespace MonthView {
  export type LayoutProps = MonthView_2.LayoutProps;
}

// @public (undocumented)
export namespace MonthView {
  export type DayScaleLayoutProps = MonthView_2.DayScaleLayoutProps;
}

// @public (undocumented)
export namespace MonthView {
  export type DayScaleCellProps = MonthView_2.DayScaleCellProps;
}

// @public (undocumented)
export namespace MonthView {
  export type DayScaleEmptyCellProps = MonthView_2.DayScaleEmptyCellProps;
}

// @public (undocumented)
export namespace MonthView {
  export type TimeTableLayoutProps = MonthView_2.TimeTableLayoutProps;
}

// @public (undocumented)
export namespace MonthView {
  export type TimeTableCellProps = MonthView_2.TimeTableCellProps;
}

// @public (undocumented)
export namespace MonthView {
  export type AppointmentLayerProps = MonthView_2.AppointmentLayerProps;
}

// @public (undocumented)
export namespace MonthView {
  export type RowProps = MonthView_2.RowProps;
}

// @public
export const MonthView: React_2.ComponentType<MonthViewProps> & {
  Layout: React_2.ComponentType<MonthView_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleLayout: React_2.ComponentType<MonthView_2.DayScaleLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleCell: React_2.ComponentType<MonthView_2.DayScaleCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleRow: React_2.ComponentType<MonthView_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleEmptyCell: React_2.ComponentType<MonthView_2.DayScaleEmptyCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableLayout: React_2.ComponentType<MonthView_2.TimeTableLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableCell: React_2.ComponentType<MonthView_2.TimeTableCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableRow: React_2.ComponentType<MonthView_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  AppointmentLayer: React_2.ComponentType<MonthView_2.AppointmentLayerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface MonthViewProps {
  appointmentLayerComponent?: React_2.ComponentType<MonthView_2.AppointmentLayerProps>;
  dayScaleCellComponent?: React_2.ComponentType<MonthView_2.DayScaleCellProps>;
  dayScaleEmptyCellComponent?: React_2.ComponentType<MonthView_2.DayScaleEmptyCellProps>;
  dayScaleLayoutComponent?: React_2.ComponentType<MonthView_2.DayScaleLayoutProps>;
  dayScaleRowComponent?: React_2.ComponentType<MonthView_2.RowProps>;
  displayName?: string;
  intervalCount?: number;
  layoutComponent?: React_2.ComponentType<MonthView_2.LayoutProps>;
  name?: string;
  timeTableCellComponent?: React_2.ComponentType<MonthView_2.TimeTableCellProps>;
  timeTableLayoutComponent?: React_2.ComponentType<MonthView_2.TimeTableLayoutProps>;
  timeTableRowComponent?: React_2.ComponentType<MonthView_2.RowProps>;
}

// @public
export const Resources: React_2.ComponentType<ResourcesProps>;

// @public (undocumented)
export interface ResourcesProps {
  data?: Array<Resource>;
  mainResourceName?: string;
  palette?: Palette;
}

// @public (undocumented)
export namespace Scheduler {
  export type RootProps = Scheduler_2.RootProps;
}

// @public
export const Scheduler: React_2.ComponentType<SchedulerProps> & {
  Root: React_2.ComponentType<Scheduler_2.RootProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface SchedulerProps {
  data?: Array<AppointmentModel>;
  firstDayOfWeek?: number;
  height?: number | `auto`;
  locale?: string | Array<string>;
  rootComponent?: React_2.ComponentType<Scheduler_2.RootProps>;
}

// @public (undocumented)
export namespace TodayButton {
  export type ButtonProps = TodayButton_2.ButtonProps;
}

// @public
export const TodayButton: React_2.ComponentType<TodayButtonProps> & {
  Button: React_2.ComponentType<TodayButton_2.ButtonProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface TodayButtonProps {
  buttonComponent?: React_2.ComponentType<TodayButton_2.ButtonProps>;
  messages?: TodayButton_2.LocalizationMessages;
}

// @public (undocumented)
export namespace Toolbar {
  export type RootProps = Toolbar_2.RootProps;
}

// @public (undocumented)
export namespace Toolbar {
  export type FlexibleSpaceProps = Toolbar_2.FlexibleSpaceProps;
}

// @public
export const Toolbar: React_2.ComponentType<ToolbarProps> & {
  Root: React_2.ComponentType<Toolbar_2.RootProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  FlexibleSpace: React_2.ComponentType<Toolbar_2.FlexibleSpaceProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface ToolbarProps {
  flexibleSpaceComponent?: React_2.ComponentType<Toolbar_2.FlexibleSpaceProps>;
  rootComponent?: React_2.ComponentType<Toolbar_2.RootProps>;
}

// @public (undocumented)
export namespace ViewSwitcher {
  export type SwitcherProps = ViewSwitcher_2.SwitcherProps;
}

// @public
export const ViewSwitcher: React_2.ComponentType<ViewSwitcherProps> & {
  Switcher: React_2.ComponentType<ViewSwitcher_2.SwitcherProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface ViewSwitcherProps {
  switcherComponent?: React_2.ComponentType<ViewSwitcher_2.SwitcherProps>;
}

// @public (undocumented)
export namespace WeekView {
  export type CellData = WeekView_2.CellData;
}

// @public (undocumented)
export namespace WeekView {
  export type LayoutProps = WeekView_2.LayoutProps;
}

// @public (undocumented)
export namespace WeekView {
  export type TimeScaleLayoutProps = WeekView_2.TimeScaleLayoutProps;
}

// @public (undocumented)
export namespace WeekView {
  export type TimeScaleLabelProps = WeekView_2.TimeScaleLabelProps;
}

// @public (undocumented)
export namespace WeekView {
  export type TimeScaleTickCellProps = WeekView_2.TimeScaleTickCellProps;
}

// @public (undocumented)
export namespace WeekView {
  export type DayScaleLayoutProps = WeekView_2.DayScaleLayoutProps;
}

// @public (undocumented)
export namespace WeekView {
  export type DayScaleCellProps = WeekView_2.DayScaleCellProps;
}

// @public (undocumented)
export namespace WeekView {
  export type DayScaleEmptyCellProps = WeekView_2.DayScaleEmptyCellProps;
}

// @public (undocumented)
export namespace WeekView {
  export type TimeTableLayoutProps = WeekView_2.TimeTableLayoutProps;
}

// @public (undocumented)
export namespace WeekView {
  export type TimeTableCellProps = WeekView_2.TimeTableCellProps;
}

// @public (undocumented)
export namespace WeekView {
  export type AppointmentLayerProps = WeekView_2.AppointmentLayerProps;
}

// @public (undocumented)
export namespace WeekView {
  export type RowProps = WeekView_2.RowProps;
}

// @public
export const WeekView: React_2.ComponentType<WeekViewProps> & {
  Layout: React_2.ComponentType<WeekView_2.LayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeScaleLayout: React_2.ComponentType<WeekView_2.TimeScaleLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeScaleLabel: React_2.ComponentType<WeekView_2.TimeScaleLabelProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeScaleTickCell: React_2.ComponentType<WeekView_2.TimeScaleTickCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleLayout: React_2.ComponentType<WeekView_2.DayScaleLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleCell: React_2.ComponentType<WeekView_2.DayScaleCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleRow: React_2.ComponentType<WeekView_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  DayScaleEmptyCell: React_2.ComponentType<WeekView_2.DayScaleEmptyCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableLayout: React_2.ComponentType<WeekView_2.TimeTableLayoutProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableCell: React_2.ComponentType<WeekView_2.TimeTableCellProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  TimeTableRow: React_2.ComponentType<WeekView_2.RowProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
  AppointmentLayer: React_2.ComponentType<WeekView_2.AppointmentLayerProps & { className?: string; style?: React_2.CSSProperties; [x: string]: any }>;
};

// @public (undocumented)
export interface WeekViewProps {
  appointmentLayerComponent?: React_2.ComponentType<WeekView_2.AppointmentLayerProps>;
  cellDuration?: number;
  dayScaleCellComponent?: React_2.ComponentType<WeekView_2.DayScaleCellProps>;
  dayScaleEmptyCellComponent?: React_2.ComponentType<WeekView_2.DayScaleEmptyCellProps>;
  dayScaleLayoutComponent?: React_2.ComponentType<WeekView_2.DayScaleLayoutProps>;
  dayScaleRowComponent?: React_2.ComponentType<WeekView_2.RowProps>;
  displayName?: string;
  endDayHour?: number;
  excludedDays?: Array<number>;
  intervalCount?: number;
  layoutComponent?: React_2.ComponentType<WeekView_2.LayoutProps>;
  name?: string;
  startDayHour?: number;
  timeScaleLabelComponent?: React_2.ComponentType<WeekView_2.TimeScaleLabelProps>;
  timeScaleLayoutComponent?: React_2.ComponentType<WeekView_2.TimeScaleLayoutProps>;
  timeScaleTickCellComponent?: React_2.ComponentType<WeekView_2.TimeScaleTickCellProps>;
  timeTableCellComponent?: React_2.ComponentType<WeekView_2.TimeTableCellProps>;
  timeTableLayoutComponent?: React_2.ComponentType<WeekView_2.TimeTableLayoutProps>;
  timeTableRowComponent?: React_2.ComponentType<WeekView_2.RowProps>;
}


// (No @packageDocumentation comment for this package)

```
